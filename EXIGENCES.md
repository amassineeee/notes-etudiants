\# Exigences de sécurité de l'application des notes



| # | Exigence : « Le système doit… » | Vérification | Étape du SDLC | Test |

|---|---|---|---|---|

| 1 | Le système doit refuser toute injection SQL dans la recherche par nom. | Test automatique pytest | Développement | S1 |

| 2 | Le système doit refuser toute modification faite sans identification (401). | Test automatique pytest | Conception | S2 |

| 3 | Le système doit refuser la modification d'une note par un étudiant (403). | Test automatique pytest | Conception | S3 |

| 4 | Le système doit refuser à un enseignant la modification des notes d'un autre module (403). | Test automatique pytest | Conception | S4 |

| 5 | Le système doit refuser toute note qui n'est pas un nombre entre 0 et 20 (400). | Test automatique pytest | Développement | S5 |

| 6 | Le système doit permettre à l'enseignant du module de modifier la note de son étudiant. | Test automatique pytest | Test | S6 |

| 7 | Le système doit n'afficher aucun détail technique en cas d'erreur. | Test automatique pytest | Développement | S7 |

