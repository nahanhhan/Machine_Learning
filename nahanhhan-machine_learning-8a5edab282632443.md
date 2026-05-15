Directory structure:
└── nahanhhan-machine_learning/
    ├── README.md
    ├── pyproject.toml
    ├── uv.lock
    ├── .python-version
    └── ML/
        ├── Binarization.ipynb
        ├── classification&regression.ipynb
        ├── cross_validation.ipynb
        ├── depth_UF_OF_GF.ipynb
        ├── Ensemble_Learning.ipynb
        ├── feature_scaling.ipynb
        ├── Gradient_Descent.ipynb
        ├── HPO.ipynb
        ├── metrics.ipynb
        ├── sklearn_dataset.ipynb
        ├── ML_introduction/
        │   ├── Reinforcement_Learning.ipynb
        │   ├── semi-supervised_learning.ipynb
        │   ├── supervised_learning.ipynb
        │   └── unsupervised_learning.ipynb
        └── ML_projects/
            └── titanic/
                ├── gender_submission.csv
                ├── test.csv
                ├── titanic.ipynb
                └── train.csv

================================================
FILE: README.md
================================================
[Empty file]


================================================
FILE: pyproject.toml
================================================
[project]
name = "machine-learning"
version = "0.1.0"
description = "Add your description here"
readme = "README.md"
requires-python = ">=3.12"
dependencies = [
    "numpy>=2.4.4",
    "pandas>=3.0.2",
    "scikit-learn>=1.8.0",
]

[dependency-groups]
dev = [
    "ipykernel>=7.2.0",
]



================================================
FILE: uv.lock
================================================
version = 1
revision = 3
requires-python = ">=3.12"
resolution-markers = [
    "python_full_version >= '3.14' and sys_platform == 'win32'",
    "python_full_version >= '3.14' and sys_platform == 'emscripten'",
    "python_full_version >= '3.14' and sys_platform != 'emscripten' and sys_platform != 'win32'",
    "python_full_version < '3.14' and sys_platform == 'win32'",
    "python_full_version < '3.14' and sys_platform == 'emscripten'",
    "python_full_version < '3.14' and sys_platform != 'emscripten' and sys_platform != 'win32'",
]

[[package]]
name = "appnope"
version = "0.1.4"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/35/5d/752690df9ef5b76e169e68d6a129fa6d08a7100ca7f754c89495db3c6019/appnope-0.1.4.tar.gz", hash = "sha256:1de3860566df9caf38f01f86f65e0e13e379af54f9e4bee1e66b48f2efffd1ee", size = 4170, upload-time = "2024-02-06T09:43:11.258Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/81/29/5ecc3a15d5a33e31b26c11426c45c501e439cb865d0bff96315d86443b78/appnope-0.1.4-py2.py3-none-any.whl", hash = "sha256:502575ee11cd7a28c0205f379b525beefebab9d161b7c964670864014ed7213c", size = 4321, upload-time = "2024-02-06T09:43:09.663Z" },
]

[[package]]
name = "asttokens"
version = "3.0.1"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/be/a5/8e3f9b6771b0b408517c82d97aed8f2036509bc247d46114925e32fe33f0/asttokens-3.0.1.tar.gz", hash = "sha256:71a4ee5de0bde6a31d64f6b13f2293ac190344478f081c3d1bccfcf5eacb0cb7", size = 62308, upload-time = "2025-11-15T16:43:48.578Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/d2/39/e7eaf1799466a4aef85b6a4fe7bd175ad2b1c6345066aa33f1f58d4b18d0/asttokens-3.0.1-py3-none-any.whl", hash = "sha256:15a3ebc0f43c2d0a50eeafea25e19046c68398e487b9f1f5b517f7c0f40f976a", size = 27047, upload-time = "2025-11-15T16:43:16.109Z" },
]

[[package]]
name = "cffi"
version = "2.0.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "pycparser", marker = "implementation_name != 'PyPy'" },
]
sdist = { url = "https://files.pythonhosted.org/packages/eb/56/b1ba7935a17738ae8453301356628e8147c79dbb825bcbc73dc7401f9846/cffi-2.0.0.tar.gz", hash = "sha256:44d1b5909021139fe36001ae048dbdde8214afa20200eda0f64c068cac5d5529", size = 523588, upload-time = "2025-09-08T23:24:04.541Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/ea/47/4f61023ea636104d4f16ab488e268b93008c3d0bb76893b1b31db1f96802/cffi-2.0.0-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:6d02d6655b0e54f54c4ef0b94eb6be0607b70853c45ce98bd278dc7de718be5d", size = 185271, upload-time = "2025-09-08T23:22:44.795Z" },
    { url = "https://files.pythonhosted.org/packages/df/a2/781b623f57358e360d62cdd7a8c681f074a71d445418a776eef0aadb4ab4/cffi-2.0.0-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:8eca2a813c1cb7ad4fb74d368c2ffbbb4789d377ee5bb8df98373c2cc0dee76c", size = 181048, upload-time = "2025-09-08T23:22:45.938Z" },
    { url = "https://files.pythonhosted.org/packages/ff/df/a4f0fbd47331ceeba3d37c2e51e9dfc9722498becbeec2bd8bc856c9538a/cffi-2.0.0-cp312-cp312-manylinux1_i686.manylinux2014_i686.manylinux_2_17_i686.manylinux_2_5_i686.whl", hash = "sha256:21d1152871b019407d8ac3985f6775c079416c282e431a4da6afe7aefd2bccbe", size = 212529, upload-time = "2025-09-08T23:22:47.349Z" },
    { url = "https://files.pythonhosted.org/packages/d5/72/12b5f8d3865bf0f87cf1404d8c374e7487dcf097a1c91c436e72e6badd83/cffi-2.0.0-cp312-cp312-manylinux2014_aarch64.manylinux_2_17_aarch64.whl", hash = "sha256:b21e08af67b8a103c71a250401c78d5e0893beff75e28c53c98f4de42f774062", size = 220097, upload-time = "2025-09-08T23:22:48.677Z" },
    { url = "https://files.pythonhosted.org/packages/c2/95/7a135d52a50dfa7c882ab0ac17e8dc11cec9d55d2c18dda414c051c5e69e/cffi-2.0.0-cp312-cp312-manylinux2014_ppc64le.manylinux_2_17_ppc64le.whl", hash = "sha256:1e3a615586f05fc4065a8b22b8152f0c1b00cdbc60596d187c2a74f9e3036e4e", size = 207983, upload-time = "2025-09-08T23:22:50.06Z" },
    { url = "https://files.pythonhosted.org/packages/3a/c8/15cb9ada8895957ea171c62dc78ff3e99159ee7adb13c0123c001a2546c1/cffi-2.0.0-cp312-cp312-manylinux2014_s390x.manylinux_2_17_s390x.whl", hash = "sha256:81afed14892743bbe14dacb9e36d9e0e504cd204e0b165062c488942b9718037", size = 206519, upload-time = "2025-09-08T23:22:51.364Z" },
    { url = "https://files.pythonhosted.org/packages/78/2d/7fa73dfa841b5ac06c7b8855cfc18622132e365f5b81d02230333ff26e9e/cffi-2.0.0-cp312-cp312-manylinux2014_x86_64.manylinux_2_17_x86_64.whl", hash = "sha256:3e17ed538242334bf70832644a32a7aae3d83b57567f9fd60a26257e992b79ba", size = 219572, upload-time = "2025-09-08T23:22:52.902Z" },
    { url = "https://files.pythonhosted.org/packages/07/e0/267e57e387b4ca276b90f0434ff88b2c2241ad72b16d31836adddfd6031b/cffi-2.0.0-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:3925dd22fa2b7699ed2617149842d2e6adde22b262fcbfada50e3d195e4b3a94", size = 222963, upload-time = "2025-09-08T23:22:54.518Z" },
    { url = "https://files.pythonhosted.org/packages/b6/75/1f2747525e06f53efbd878f4d03bac5b859cbc11c633d0fb81432d98a795/cffi-2.0.0-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:2c8f814d84194c9ea681642fd164267891702542f028a15fc97d4674b6206187", size = 221361, upload-time = "2025-09-08T23:22:55.867Z" },
    { url = "https://files.pythonhosted.org/packages/7b/2b/2b6435f76bfeb6bbf055596976da087377ede68df465419d192acf00c437/cffi-2.0.0-cp312-cp312-win32.whl", hash = "sha256:da902562c3e9c550df360bfa53c035b2f241fed6d9aef119048073680ace4a18", size = 172932, upload-time = "2025-09-08T23:22:57.188Z" },
    { url = "https://files.pythonhosted.org/packages/f8/ed/13bd4418627013bec4ed6e54283b1959cf6db888048c7cf4b4c3b5b36002/cffi-2.0.0-cp312-cp312-win_amd64.whl", hash = "sha256:da68248800ad6320861f129cd9c1bf96ca849a2771a59e0344e88681905916f5", size = 183557, upload-time = "2025-09-08T23:22:58.351Z" },
    { url = "https://files.pythonhosted.org/packages/95/31/9f7f93ad2f8eff1dbc1c3656d7ca5bfd8fb52c9d786b4dcf19b2d02217fa/cffi-2.0.0-cp312-cp312-win_arm64.whl", hash = "sha256:4671d9dd5ec934cb9a73e7ee9676f9362aba54f7f34910956b84d727b0d73fb6", size = 177762, upload-time = "2025-09-08T23:22:59.668Z" },
    { url = "https://files.pythonhosted.org/packages/4b/8d/a0a47a0c9e413a658623d014e91e74a50cdd2c423f7ccfd44086ef767f90/cffi-2.0.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:00bdf7acc5f795150faa6957054fbbca2439db2f775ce831222b66f192f03beb", size = 185230, upload-time = "2025-09-08T23:23:00.879Z" },
    { url = "https://files.pythonhosted.org/packages/4a/d2/a6c0296814556c68ee32009d9c2ad4f85f2707cdecfd7727951ec228005d/cffi-2.0.0-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:45d5e886156860dc35862657e1494b9bae8dfa63bf56796f2fb56e1679fc0bca", size = 181043, upload-time = "2025-09-08T23:23:02.231Z" },
    { url = "https://files.pythonhosted.org/packages/b0/1e/d22cc63332bd59b06481ceaac49d6c507598642e2230f201649058a7e704/cffi-2.0.0-cp313-cp313-manylinux1_i686.manylinux2014_i686.manylinux_2_17_i686.manylinux_2_5_i686.whl", hash = "sha256:07b271772c100085dd28b74fa0cd81c8fb1a3ba18b21e03d7c27f3436a10606b", size = 212446, upload-time = "2025-09-08T23:23:03.472Z" },
    { url = "https://files.pythonhosted.org/packages/a9/f5/a2c23eb03b61a0b8747f211eb716446c826ad66818ddc7810cc2cc19b3f2/cffi-2.0.0-cp313-cp313-manylinux2014_aarch64.manylinux_2_17_aarch64.whl", hash = "sha256:d48a880098c96020b02d5a1f7d9251308510ce8858940e6fa99ece33f610838b", size = 220101, upload-time = "2025-09-08T23:23:04.792Z" },
    { url = "https://files.pythonhosted.org/packages/f2/7f/e6647792fc5850d634695bc0e6ab4111ae88e89981d35ac269956605feba/cffi-2.0.0-cp313-cp313-manylinux2014_ppc64le.manylinux_2_17_ppc64le.whl", hash = "sha256:f93fd8e5c8c0a4aa1f424d6173f14a892044054871c771f8566e4008eaa359d2", size = 207948, upload-time = "2025-09-08T23:23:06.127Z" },
    { url = "https://files.pythonhosted.org/packages/cb/1e/a5a1bd6f1fb30f22573f76533de12a00bf274abcdc55c8edab639078abb6/cffi-2.0.0-cp313-cp313-manylinux2014_s390x.manylinux_2_17_s390x.whl", hash = "sha256:dd4f05f54a52fb558f1ba9f528228066954fee3ebe629fc1660d874d040ae5a3", size = 206422, upload-time = "2025-09-08T23:23:07.753Z" },
    { url = "https://files.pythonhosted.org/packages/98/df/0a1755e750013a2081e863e7cd37e0cdd02664372c754e5560099eb7aa44/cffi-2.0.0-cp313-cp313-manylinux2014_x86_64.manylinux_2_17_x86_64.whl", hash = "sha256:c8d3b5532fc71b7a77c09192b4a5a200ea992702734a2e9279a37f2478236f26", size = 219499, upload-time = "2025-09-08T23:23:09.648Z" },
    { url = "https://files.pythonhosted.org/packages/50/e1/a969e687fcf9ea58e6e2a928ad5e2dd88cc12f6f0ab477e9971f2309b57c/cffi-2.0.0-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:d9b29c1f0ae438d5ee9acb31cadee00a58c46cc9c0b2f9038c6b0b3470877a8c", size = 222928, upload-time = "2025-09-08T23:23:10.928Z" },
    { url = "https://files.pythonhosted.org/packages/36/54/0362578dd2c9e557a28ac77698ed67323ed5b9775ca9d3fe73fe191bb5d8/cffi-2.0.0-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:6d50360be4546678fc1b79ffe7a66265e28667840010348dd69a314145807a1b", size = 221302, upload-time = "2025-09-08T23:23:12.42Z" },
    { url = "https://files.pythonhosted.org/packages/eb/6d/bf9bda840d5f1dfdbf0feca87fbdb64a918a69bca42cfa0ba7b137c48cb8/cffi-2.0.0-cp313-cp313-win32.whl", hash = "sha256:74a03b9698e198d47562765773b4a8309919089150a0bb17d829ad7b44b60d27", size = 172909, upload-time = "2025-09-08T23:23:14.32Z" },
    { url = "https://files.pythonhosted.org/packages/37/18/6519e1ee6f5a1e579e04b9ddb6f1676c17368a7aba48299c3759bbc3c8b3/cffi-2.0.0-cp313-cp313-win_amd64.whl", hash = "sha256:19f705ada2530c1167abacb171925dd886168931e0a7b78f5bffcae5c6b5be75", size = 183402, upload-time = "2025-09-08T23:23:15.535Z" },
    { url = "https://files.pythonhosted.org/packages/cb/0e/02ceeec9a7d6ee63bb596121c2c8e9b3a9e150936f4fbef6ca1943e6137c/cffi-2.0.0-cp313-cp313-win_arm64.whl", hash = "sha256:256f80b80ca3853f90c21b23ee78cd008713787b1b1e93eae9f3d6a7134abd91", size = 177780, upload-time = "2025-09-08T23:23:16.761Z" },
    { url = "https://files.pythonhosted.org/packages/92/c4/3ce07396253a83250ee98564f8d7e9789fab8e58858f35d07a9a2c78de9f/cffi-2.0.0-cp314-cp314-macosx_10_13_x86_64.whl", hash = "sha256:fc33c5141b55ed366cfaad382df24fe7dcbc686de5be719b207bb248e3053dc5", size = 185320, upload-time = "2025-09-08T23:23:18.087Z" },
    { url = "https://files.pythonhosted.org/packages/59/dd/27e9fa567a23931c838c6b02d0764611c62290062a6d4e8ff7863daf9730/cffi-2.0.0-cp314-cp314-macosx_11_0_arm64.whl", hash = "sha256:c654de545946e0db659b3400168c9ad31b5d29593291482c43e3564effbcee13", size = 181487, upload-time = "2025-09-08T23:23:19.622Z" },
    { url = "https://files.pythonhosted.org/packages/d6/43/0e822876f87ea8a4ef95442c3d766a06a51fc5298823f884ef87aaad168c/cffi-2.0.0-cp314-cp314-manylinux2014_aarch64.manylinux_2_17_aarch64.whl", hash = "sha256:24b6f81f1983e6df8db3adc38562c83f7d4a0c36162885ec7f7b77c7dcbec97b", size = 220049, upload-time = "2025-09-08T23:23:20.853Z" },
    { url = "https://files.pythonhosted.org/packages/b4/89/76799151d9c2d2d1ead63c2429da9ea9d7aac304603de0c6e8764e6e8e70/cffi-2.0.0-cp314-cp314-manylinux2014_ppc64le.manylinux_2_17_ppc64le.whl", hash = "sha256:12873ca6cb9b0f0d3a0da705d6086fe911591737a59f28b7936bdfed27c0d47c", size = 207793, upload-time = "2025-09-08T23:23:22.08Z" },
    { url = "https://files.pythonhosted.org/packages/bb/dd/3465b14bb9e24ee24cb88c9e3730f6de63111fffe513492bf8c808a3547e/cffi-2.0.0-cp314-cp314-manylinux2014_s390x.manylinux_2_17_s390x.whl", hash = "sha256:d9b97165e8aed9272a6bb17c01e3cc5871a594a446ebedc996e2397a1c1ea8ef", size = 206300, upload-time = "2025-09-08T23:23:23.314Z" },
    { url = "https://files.pythonhosted.org/packages/47/d9/d83e293854571c877a92da46fdec39158f8d7e68da75bf73581225d28e90/cffi-2.0.0-cp314-cp314-manylinux2014_x86_64.manylinux_2_17_x86_64.whl", hash = "sha256:afb8db5439b81cf9c9d0c80404b60c3cc9c3add93e114dcae767f1477cb53775", size = 219244, upload-time = "2025-09-08T23:23:24.541Z" },
    { url = "https://files.pythonhosted.org/packages/2b/0f/1f177e3683aead2bb00f7679a16451d302c436b5cbf2505f0ea8146ef59e/cffi-2.0.0-cp314-cp314-musllinux_1_2_aarch64.whl", hash = "sha256:737fe7d37e1a1bffe70bd5754ea763a62a066dc5913ca57e957824b72a85e205", size = 222828, upload-time = "2025-09-08T23:23:26.143Z" },
    { url = "https://files.pythonhosted.org/packages/c6/0f/cafacebd4b040e3119dcb32fed8bdef8dfe94da653155f9d0b9dc660166e/cffi-2.0.0-cp314-cp314-musllinux_1_2_x86_64.whl", hash = "sha256:38100abb9d1b1435bc4cc340bb4489635dc2f0da7456590877030c9b3d40b0c1", size = 220926, upload-time = "2025-09-08T23:23:27.873Z" },
    { url = "https://files.pythonhosted.org/packages/3e/aa/df335faa45b395396fcbc03de2dfcab242cd61a9900e914fe682a59170b1/cffi-2.0.0-cp314-cp314-win32.whl", hash = "sha256:087067fa8953339c723661eda6b54bc98c5625757ea62e95eb4898ad5e776e9f", size = 175328, upload-time = "2025-09-08T23:23:44.61Z" },
    { url = "https://files.pythonhosted.org/packages/bb/92/882c2d30831744296ce713f0feb4c1cd30f346ef747b530b5318715cc367/cffi-2.0.0-cp314-cp314-win_amd64.whl", hash = "sha256:203a48d1fb583fc7d78a4c6655692963b860a417c0528492a6bc21f1aaefab25", size = 185650, upload-time = "2025-09-08T23:23:45.848Z" },
    { url = "https://files.pythonhosted.org/packages/9f/2c/98ece204b9d35a7366b5b2c6539c350313ca13932143e79dc133ba757104/cffi-2.0.0-cp314-cp314-win_arm64.whl", hash = "sha256:dbd5c7a25a7cb98f5ca55d258b103a2054f859a46ae11aaf23134f9cc0d356ad", size = 180687, upload-time = "2025-09-08T23:23:47.105Z" },
    { url = "https://files.pythonhosted.org/packages/3e/61/c768e4d548bfa607abcda77423448df8c471f25dbe64fb2ef6d555eae006/cffi-2.0.0-cp314-cp314t-macosx_10_13_x86_64.whl", hash = "sha256:9a67fc9e8eb39039280526379fb3a70023d77caec1852002b4da7e8b270c4dd9", size = 188773, upload-time = "2025-09-08T23:23:29.347Z" },
    { url = "https://files.pythonhosted.org/packages/2c/ea/5f76bce7cf6fcd0ab1a1058b5af899bfbef198bea4d5686da88471ea0336/cffi-2.0.0-cp314-cp314t-macosx_11_0_arm64.whl", hash = "sha256:7a66c7204d8869299919db4d5069a82f1561581af12b11b3c9f48c584eb8743d", size = 185013, upload-time = "2025-09-08T23:23:30.63Z" },
    { url = "https://files.pythonhosted.org/packages/be/b4/c56878d0d1755cf9caa54ba71e5d049479c52f9e4afc230f06822162ab2f/cffi-2.0.0-cp314-cp314t-manylinux2014_aarch64.manylinux_2_17_aarch64.whl", hash = "sha256:7cc09976e8b56f8cebd752f7113ad07752461f48a58cbba644139015ac24954c", size = 221593, upload-time = "2025-09-08T23:23:31.91Z" },
    { url = "https://files.pythonhosted.org/packages/e0/0d/eb704606dfe8033e7128df5e90fee946bbcb64a04fcdaa97321309004000/cffi-2.0.0-cp314-cp314t-manylinux2014_ppc64le.manylinux_2_17_ppc64le.whl", hash = "sha256:92b68146a71df78564e4ef48af17551a5ddd142e5190cdf2c5624d0c3ff5b2e8", size = 209354, upload-time = "2025-09-08T23:23:33.214Z" },
    { url = "https://files.pythonhosted.org/packages/d8/19/3c435d727b368ca475fb8742ab97c9cb13a0de600ce86f62eab7fa3eea60/cffi-2.0.0-cp314-cp314t-manylinux2014_s390x.manylinux_2_17_s390x.whl", hash = "sha256:b1e74d11748e7e98e2f426ab176d4ed720a64412b6a15054378afdb71e0f37dc", size = 208480, upload-time = "2025-09-08T23:23:34.495Z" },
    { url = "https://files.pythonhosted.org/packages/d0/44/681604464ed9541673e486521497406fadcc15b5217c3e326b061696899a/cffi-2.0.0-cp314-cp314t-manylinux2014_x86_64.manylinux_2_17_x86_64.whl", hash = "sha256:28a3a209b96630bca57cce802da70c266eb08c6e97e5afd61a75611ee6c64592", size = 221584, upload-time = "2025-09-08T23:23:36.096Z" },
    { url = "https://files.pythonhosted.org/packages/25/8e/342a504ff018a2825d395d44d63a767dd8ebc927ebda557fecdaca3ac33a/cffi-2.0.0-cp314-cp314t-musllinux_1_2_aarch64.whl", hash = "sha256:7553fb2090d71822f02c629afe6042c299edf91ba1bf94951165613553984512", size = 224443, upload-time = "2025-09-08T23:23:37.328Z" },
    { url = "https://files.pythonhosted.org/packages/e1/5e/b666bacbbc60fbf415ba9988324a132c9a7a0448a9a8f125074671c0f2c3/cffi-2.0.0-cp314-cp314t-musllinux_1_2_x86_64.whl", hash = "sha256:6c6c373cfc5c83a975506110d17457138c8c63016b563cc9ed6e056a82f13ce4", size = 223437, upload-time = "2025-09-08T23:23:38.945Z" },
    { url = "https://files.pythonhosted.org/packages/a0/1d/ec1a60bd1a10daa292d3cd6bb0b359a81607154fb8165f3ec95fe003b85c/cffi-2.0.0-cp314-cp314t-win32.whl", hash = "sha256:1fc9ea04857caf665289b7a75923f2c6ed559b8298a1b8c49e59f7dd95c8481e", size = 180487, upload-time = "2025-09-08T23:23:40.423Z" },
    { url = "https://files.pythonhosted.org/packages/bf/41/4c1168c74fac325c0c8156f04b6749c8b6a8f405bbf91413ba088359f60d/cffi-2.0.0-cp314-cp314t-win_amd64.whl", hash = "sha256:d68b6cef7827e8641e8ef16f4494edda8b36104d79773a334beaa1e3521430f6", size = 191726, upload-time = "2025-09-08T23:23:41.742Z" },
    { url = "https://files.pythonhosted.org/packages/ae/3a/dbeec9d1ee0844c679f6bb5d6ad4e9f198b1224f4e7a32825f47f6192b0c/cffi-2.0.0-cp314-cp314t-win_arm64.whl", hash = "sha256:0a1527a803f0a659de1af2e1fd700213caba79377e27e4693648c2923da066f9", size = 184195, upload-time = "2025-09-08T23:23:43.004Z" },
]

[[package]]
name = "colorama"
version = "0.4.6"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/d8/53/6f443c9a4a8358a93a6792e2acffb9d9d5cb0a5cfd8802644b7b1c9a02e4/colorama-0.4.6.tar.gz", hash = "sha256:08695f5cb7ed6e0531a20572697297273c47b8cae5a63ffc6d6ed5c201be6e44", size = 27697, upload-time = "2022-10-25T02:36:22.414Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/d1/d6/3965ed04c63042e047cb6a3e6ed1a63a35087b6a609aa3a15ed8ac56c221/colorama-0.4.6-py2.py3-none-any.whl", hash = "sha256:4f1d9991f5acc0ca119f9d443620b77f9d6b33703e51011c16baf57afb285fc6", size = 25335, upload-time = "2022-10-25T02:36:20.889Z" },
]

[[package]]
name = "comm"
version = "0.2.3"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/4c/13/7d740c5849255756bc17888787313b61fd38a0a8304fc4f073dfc46122aa/comm-0.2.3.tar.gz", hash = "sha256:2dc8048c10962d55d7ad693be1e7045d891b7ce8d999c97963a5e3e99c055971", size = 6319, upload-time = "2025-07-25T14:02:04.452Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/60/97/891a0971e1e4a8c5d2b20bbe0e524dc04548d2307fee33cdeba148fd4fc7/comm-0.2.3-py3-none-any.whl", hash = "sha256:c615d91d75f7f04f095b30d1c1711babd43bdc6419c1be9886a85f2f4e489417", size = 7294, upload-time = "2025-07-25T14:02:02.896Z" },
]

[[package]]
name = "debugpy"
version = "1.8.20"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/e0/b7/cd8080344452e4874aae67c40d8940e2b4d47b01601a8fd9f44786c757c7/debugpy-1.8.20.tar.gz", hash = "sha256:55bc8701714969f1ab89a6d5f2f3d40c36f91b2cbe2f65d98bf8196f6a6a2c33", size = 1645207, upload-time = "2026-01-29T23:03:28.199Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/14/57/7f34f4736bfb6e00f2e4c96351b07805d83c9a7b33d28580ae01374430f7/debugpy-1.8.20-cp312-cp312-macosx_15_0_universal2.whl", hash = "sha256:4ae3135e2089905a916909ef31922b2d733d756f66d87345b3e5e52b7a55f13d", size = 2550686, upload-time = "2026-01-29T23:03:42.023Z" },
    { url = "https://files.pythonhosted.org/packages/ab/78/b193a3975ca34458f6f0e24aaf5c3e3da72f5401f6054c0dfd004b41726f/debugpy-1.8.20-cp312-cp312-manylinux_2_34_x86_64.whl", hash = "sha256:88f47850a4284b88bd2bfee1f26132147d5d504e4e86c22485dfa44b97e19b4b", size = 4310588, upload-time = "2026-01-29T23:03:43.314Z" },
    { url = "https://files.pythonhosted.org/packages/c1/55/f14deb95eaf4f30f07ef4b90a8590fc05d9e04df85ee379712f6fb6736d7/debugpy-1.8.20-cp312-cp312-win32.whl", hash = "sha256:4057ac68f892064e5f98209ab582abfee3b543fb55d2e87610ddc133a954d390", size = 5331372, upload-time = "2026-01-29T23:03:45.526Z" },
    { url = "https://files.pythonhosted.org/packages/a1/39/2bef246368bd42f9bd7cba99844542b74b84dacbdbea0833e610f384fee8/debugpy-1.8.20-cp312-cp312-win_amd64.whl", hash = "sha256:a1a8f851e7cf171330679ef6997e9c579ef6dd33c9098458bd9986a0f4ca52e3", size = 5372835, upload-time = "2026-01-29T23:03:47.245Z" },
    { url = "https://files.pythonhosted.org/packages/15/e2/fc500524cc6f104a9d049abc85a0a8b3f0d14c0a39b9c140511c61e5b40b/debugpy-1.8.20-cp313-cp313-macosx_15_0_universal2.whl", hash = "sha256:5dff4bb27027821fdfcc9e8f87309a28988231165147c31730128b1c983e282a", size = 2539560, upload-time = "2026-01-29T23:03:48.738Z" },
    { url = "https://files.pythonhosted.org/packages/90/83/fb33dcea789ed6018f8da20c5a9bc9d82adc65c0c990faed43f7c955da46/debugpy-1.8.20-cp313-cp313-manylinux_2_34_x86_64.whl", hash = "sha256:84562982dd7cf5ebebfdea667ca20a064e096099997b175fe204e86817f64eaf", size = 4293272, upload-time = "2026-01-29T23:03:50.169Z" },
    { url = "https://files.pythonhosted.org/packages/a6/25/b1e4a01bfb824d79a6af24b99ef291e24189080c93576dfd9b1a2815cd0f/debugpy-1.8.20-cp313-cp313-win32.whl", hash = "sha256:da11dea6447b2cadbf8ce2bec59ecea87cc18d2c574980f643f2d2dfe4862393", size = 5331208, upload-time = "2026-01-29T23:03:51.547Z" },
    { url = "https://files.pythonhosted.org/packages/13/f7/a0b368ce54ffff9e9028c098bd2d28cfc5b54f9f6c186929083d4c60ba58/debugpy-1.8.20-cp313-cp313-win_amd64.whl", hash = "sha256:eb506e45943cab2efb7c6eafdd65b842f3ae779f020c82221f55aca9de135ed7", size = 5372930, upload-time = "2026-01-29T23:03:53.585Z" },
    { url = "https://files.pythonhosted.org/packages/33/2e/f6cb9a8a13f5058f0a20fe09711a7b726232cd5a78c6a7c05b2ec726cff9/debugpy-1.8.20-cp314-cp314-macosx_15_0_universal2.whl", hash = "sha256:9c74df62fc064cd5e5eaca1353a3ef5a5d50da5eb8058fcef63106f7bebe6173", size = 2538066, upload-time = "2026-01-29T23:03:54.999Z" },
    { url = "https://files.pythonhosted.org/packages/c5/56/6ddca50b53624e1ca3ce1d1e49ff22db46c47ea5fb4c0cc5c9b90a616364/debugpy-1.8.20-cp314-cp314-manylinux_2_34_x86_64.whl", hash = "sha256:077a7447589ee9bc1ff0cdf443566d0ecf540ac8aa7333b775ebcb8ce9f4ecad", size = 4269425, upload-time = "2026-01-29T23:03:56.518Z" },
    { url = "https://files.pythonhosted.org/packages/c5/d9/d64199c14a0d4c476df46c82470a3ce45c8d183a6796cfb5e66533b3663c/debugpy-1.8.20-cp314-cp314-win32.whl", hash = "sha256:352036a99dd35053b37b7803f748efc456076f929c6a895556932eaf2d23b07f", size = 5331407, upload-time = "2026-01-29T23:03:58.481Z" },
    { url = "https://files.pythonhosted.org/packages/e0/d9/1f07395b54413432624d61524dfd98c1a7c7827d2abfdb8829ac92638205/debugpy-1.8.20-cp314-cp314-win_amd64.whl", hash = "sha256:a98eec61135465b062846112e5ecf2eebb855305acc1dfbae43b72903b8ab5be", size = 5372521, upload-time = "2026-01-29T23:03:59.864Z" },
    { url = "https://files.pythonhosted.org/packages/e0/c3/7f67dea8ccf8fdcb9c99033bbe3e90b9e7395415843accb81428c441be2d/debugpy-1.8.20-py2.py3-none-any.whl", hash = "sha256:5be9bed9ae3be00665a06acaa48f8329d2b9632f15fd09f6a9a8c8d9907e54d7", size = 5337658, upload-time = "2026-01-29T23:04:17.404Z" },
]

[[package]]
name = "decorator"
version = "5.2.1"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/43/fa/6d96a0978d19e17b68d634497769987b16c8f4cd0a7a05048bec693caa6b/decorator-5.2.1.tar.gz", hash = "sha256:65f266143752f734b0a7cc83c46f4618af75b8c5911b00ccb61d0ac9b6da0360", size = 56711, upload-time = "2025-02-24T04:41:34.073Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/4e/8c/f3147f5c4b73e7550fe5f9352eaa956ae838d5c51eb58e7a25b9f3e2643b/decorator-5.2.1-py3-none-any.whl", hash = "sha256:d316bb415a2d9e2d2b3abcc4084c6502fc09240e292cd76a76afc106a1c8e04a", size = 9190, upload-time = "2025-02-24T04:41:32.565Z" },
]

[[package]]
name = "executing"
version = "2.2.1"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/cc/28/c14e053b6762b1044f34a13aab6859bbf40456d37d23aa286ac24cfd9a5d/executing-2.2.1.tar.gz", hash = "sha256:3632cc370565f6648cc328b32435bd120a1e4ebb20c77e3fdde9a13cd1e533c4", size = 1129488, upload-time = "2025-09-01T09:48:10.866Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/c1/ea/53f2148663b321f21b5a606bd5f191517cf40b7072c0497d3c92c4a13b1e/executing-2.2.1-py2.py3-none-any.whl", hash = "sha256:760643d3452b4d777d295bb167ccc74c64a81df23fb5e08eff250c425a4b2017", size = 28317, upload-time = "2025-09-01T09:48:08.5Z" },
]

[[package]]
name = "ipykernel"
version = "7.2.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "appnope", marker = "sys_platform == 'darwin'" },
    { name = "comm" },
    { name = "debugpy" },
    { name = "ipython" },
    { name = "jupyter-client" },
    { name = "jupyter-core" },
    { name = "matplotlib-inline" },
    { name = "nest-asyncio" },
    { name = "packaging" },
    { name = "psutil" },
    { name = "pyzmq" },
    { name = "tornado" },
    { name = "traitlets" },
]
sdist = { url = "https://files.pythonhosted.org/packages/ca/8d/b68b728e2d06b9e0051019640a40a9eb7a88fcd82c2e1b5ce70bef5ff044/ipykernel-7.2.0.tar.gz", hash = "sha256:18ed160b6dee2cbb16e5f3575858bc19d8f1fe6046a9a680c708494ce31d909e", size = 176046, upload-time = "2026-02-06T16:43:27.403Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/82/b9/e73d5d9f405cba7706c539aa8b311b49d4c2f3d698d9c12f815231169c71/ipykernel-7.2.0-py3-none-any.whl", hash = "sha256:3bbd4420d2b3cc105cbdf3756bfc04500b1e52f090a90716851f3916c62e1661", size = 118788, upload-time = "2026-02-06T16:43:25.149Z" },
]

[[package]]
name = "ipython"
version = "9.13.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "colorama", marker = "sys_platform == 'win32'" },
    { name = "decorator" },
    { name = "ipython-pygments-lexers" },
    { name = "jedi" },
    { name = "matplotlib-inline" },
    { name = "pexpect", marker = "sys_platform != 'emscripten' and sys_platform != 'win32'" },
    { name = "prompt-toolkit" },
    { name = "psutil" },
    { name = "pygments" },
    { name = "stack-data" },
    { name = "traitlets" },
]
sdist = { url = "https://files.pythonhosted.org/packages/cd/c4/87cda5842cf5c31837c06ddb588e11c3c35d8ece89b7a0108c06b8c9b00a/ipython-9.13.0.tar.gz", hash = "sha256:7e834b6afc99f020e3f05966ced34792f40267d64cb1ea9043886dab0dde5967", size = 4430549, upload-time = "2026-04-24T12:24:55.221Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/b9/86/3060e8029b7cc505cce9a0137431dda81d0a3fde93a8f0f50ee0bf37a795/ipython-9.13.0-py3-none-any.whl", hash = "sha256:57f9d4639e20818d328d287c7b549af3d05f12486ea8f2e7f73e52a36ec4d201", size = 627274, upload-time = "2026-04-24T12:24:53.038Z" },
]

[[package]]
name = "ipython-pygments-lexers"
version = "1.1.1"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "pygments" },
]
sdist = { url = "https://files.pythonhosted.org/packages/ef/4c/5dd1d8af08107f88c7f741ead7a40854b8ac24ddf9ae850afbcf698aa552/ipython_pygments_lexers-1.1.1.tar.gz", hash = "sha256:09c0138009e56b6854f9535736f4171d855c8c08a563a0dcd8022f78355c7e81", size = 8393, upload-time = "2025-01-17T11:24:34.505Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/d9/33/1f075bf72b0b747cb3288d011319aaf64083cf2efef8354174e3ed4540e2/ipython_pygments_lexers-1.1.1-py3-none-any.whl", hash = "sha256:a9462224a505ade19a605f71f8fa63c2048833ce50abc86768a0d81d876dc81c", size = 8074, upload-time = "2025-01-17T11:24:33.271Z" },
]

[[package]]
name = "jedi"
version = "0.19.2"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "parso" },
]
sdist = { url = "https://files.pythonhosted.org/packages/72/3a/79a912fbd4d8dd6fbb02bf69afd3bb72cf0c729bb3063c6f4498603db17a/jedi-0.19.2.tar.gz", hash = "sha256:4770dc3de41bde3966b02eb84fbcf557fb33cce26ad23da12c742fb50ecb11f0", size = 1231287, upload-time = "2024-11-11T01:41:42.873Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/c0/5a/9cac0c82afec3d09ccd97c8b6502d48f165f9124db81b4bcb90b4af974ee/jedi-0.19.2-py2.py3-none-any.whl", hash = "sha256:a8ef22bde8490f57fe5c7681a3c83cb58874daf72b4784de3cce5b6ef6edb5b9", size = 1572278, upload-time = "2024-11-11T01:41:40.175Z" },
]

[[package]]
name = "joblib"
version = "1.5.3"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/41/f2/d34e8b3a08a9cc79a50b2208a93dce981fe615b64d5a4d4abee421d898df/joblib-1.5.3.tar.gz", hash = "sha256:8561a3269e6801106863fd0d6d84bb737be9e7631e33aaed3fb9ce5953688da3", size = 331603, upload-time = "2025-12-15T08:41:46.427Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/7b/91/984aca2ec129e2757d1e4e3c81c3fcda9d0f85b74670a094cc443d9ee949/joblib-1.5.3-py3-none-any.whl", hash = "sha256:5fc3c5039fc5ca8c0276333a188bbd59d6b7ab37fe6632daa76bc7f9ec18e713", size = 309071, upload-time = "2025-12-15T08:41:44.973Z" },
]

[[package]]
name = "jupyter-client"
version = "8.8.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "jupyter-core" },
    { name = "python-dateutil" },
    { name = "pyzmq" },
    { name = "tornado" },
    { name = "traitlets" },
]
sdist = { url = "https://files.pythonhosted.org/packages/05/e4/ba649102a3bc3fbca54e7239fb924fd434c766f855693d86de0b1f2bec81/jupyter_client-8.8.0.tar.gz", hash = "sha256:d556811419a4f2d96c869af34e854e3f059b7cc2d6d01a9cd9c85c267691be3e", size = 348020, upload-time = "2026-01-08T13:55:47.938Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/2d/0b/ceb7694d864abc0a047649aec263878acb9f792e1fec3e676f22dc9015e3/jupyter_client-8.8.0-py3-none-any.whl", hash = "sha256:f93a5b99c5e23a507b773d3a1136bd6e16c67883ccdbd9a829b0bbdb98cd7d7a", size = 107371, upload-time = "2026-01-08T13:55:45.562Z" },
]

[[package]]
name = "jupyter-core"
version = "5.9.1"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "platformdirs" },
    { name = "traitlets" },
]
sdist = { url = "https://files.pythonhosted.org/packages/02/49/9d1284d0dc65e2c757b74c6687b6d319b02f822ad039e5c512df9194d9dd/jupyter_core-5.9.1.tar.gz", hash = "sha256:4d09aaff303b9566c3ce657f580bd089ff5c91f5f89cf7d8846c3cdf465b5508", size = 89814, upload-time = "2025-10-16T19:19:18.444Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/e7/e7/80988e32bf6f73919a113473a604f5a8f09094de312b9d52b79c2df7612b/jupyter_core-5.9.1-py3-none-any.whl", hash = "sha256:ebf87fdc6073d142e114c72c9e29a9d7ca03fad818c5d300ce2adc1fb0743407", size = 29032, upload-time = "2025-10-16T19:19:16.783Z" },
]

[[package]]
name = "machine-learning"
version = "0.1.0"
source = { virtual = "." }
dependencies = [
    { name = "numpy" },
    { name = "pandas" },
    { name = "scikit-learn" },
]

[package.dev-dependencies]
dev = [
    { name = "ipykernel" },
]

[package.metadata]
requires-dist = [
    { name = "numpy", specifier = ">=2.4.4" },
    { name = "pandas", specifier = ">=3.0.2" },
    { name = "scikit-learn", specifier = ">=1.8.0" },
]

[package.metadata.requires-dev]
dev = [{ name = "ipykernel", specifier = ">=7.2.0" }]

[[package]]
name = "matplotlib-inline"
version = "0.2.1"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "traitlets" },
]
sdist = { url = "https://files.pythonhosted.org/packages/c7/74/97e72a36efd4ae2bccb3463284300f8953f199b5ffbc04cbbb0ec78f74b1/matplotlib_inline-0.2.1.tar.gz", hash = "sha256:e1ee949c340d771fc39e241ea75683deb94762c8fa5f2927ec57c83c4dffa9fe", size = 8110, upload-time = "2025-10-23T09:00:22.126Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/af/33/ee4519fa02ed11a94aef9559552f3b17bb863f2ecfe1a35dc7f548cde231/matplotlib_inline-0.2.1-py3-none-any.whl", hash = "sha256:d56ce5156ba6085e00a9d54fead6ed29a9c47e215cd1bba2e976ef39f5710a76", size = 9516, upload-time = "2025-10-23T09:00:20.675Z" },
]

[[package]]
name = "nest-asyncio"
version = "1.6.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/83/f8/51569ac65d696c8ecbee95938f89d4abf00f47d58d48f6fbabfe8f0baefe/nest_asyncio-1.6.0.tar.gz", hash = "sha256:6f172d5449aca15afd6c646851f4e31e02c598d553a667e38cafa997cfec55fe", size = 7418, upload-time = "2024-01-21T14:25:19.227Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/a0/c4/c2971a3ba4c6103a3d10c4b0f24f461ddc027f0f09763220cf35ca1401b3/nest_asyncio-1.6.0-py3-none-any.whl", hash = "sha256:87af6efd6b5e897c81050477ef65c62e2b2f35d51703cae01aff2905b1852e1c", size = 5195, upload-time = "2024-01-21T14:25:17.223Z" },
]

[[package]]
name = "numpy"
version = "2.4.4"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/d7/9f/b8cef5bffa569759033adda9481211426f12f53299629b410340795c2514/numpy-2.4.4.tar.gz", hash = "sha256:2d390634c5182175533585cc89f3608a4682ccb173cc9bb940b2881c8d6f8fa0", size = 20731587, upload-time = "2026-03-29T13:22:01.298Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/28/05/32396bec30fb2263770ee910142f49c1476d08e8ad41abf8403806b520ce/numpy-2.4.4-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:15716cfef24d3a9762e3acdf87e27f58dc823d1348f765bbea6bef8c639bfa1b", size = 16689272, upload-time = "2026-03-29T13:18:49.223Z" },
    { url = "https://files.pythonhosted.org/packages/c5/f3/a983d28637bfcd763a9c7aafdb6d5c0ebf3d487d1e1459ffdb57e2f01117/numpy-2.4.4-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:23cbfd4c17357c81021f21540da84ee282b9c8fba38a03b7b9d09ba6b951421e", size = 14699573, upload-time = "2026-03-29T13:18:52.629Z" },
    { url = "https://files.pythonhosted.org/packages/9b/fd/e5ecca1e78c05106d98028114f5c00d3eddb41207686b2b7de3e477b0e22/numpy-2.4.4-cp312-cp312-macosx_14_0_arm64.whl", hash = "sha256:8b3b60bb7cba2c8c81837661c488637eee696f59a877788a396d33150c35d842", size = 5204782, upload-time = "2026-03-29T13:18:55.579Z" },
    { url = "https://files.pythonhosted.org/packages/de/2f/702a4594413c1a8632092beae8aba00f1d67947389369b3777aed783fdca/numpy-2.4.4-cp312-cp312-macosx_14_0_x86_64.whl", hash = "sha256:e4a010c27ff6f210ff4c6ef34394cd61470d01014439b192ec22552ee867f2a8", size = 6552038, upload-time = "2026-03-29T13:18:57.769Z" },
    { url = "https://files.pythonhosted.org/packages/7f/37/eed308a8f56cba4d1fdf467a4fc67ef4ff4bf1c888f5fc980481890104b1/numpy-2.4.4-cp312-cp312-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:f9e75681b59ddaa5e659898085ae0eaea229d054f2ac0c7e563a62205a700121", size = 15670666, upload-time = "2026-03-29T13:19:00.341Z" },
    { url = "https://files.pythonhosted.org/packages/0a/0d/0e3ecece05b7a7e87ab9fb587855548da437a061326fff64a223b6dcb78a/numpy-2.4.4-cp312-cp312-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:81f4a14bee47aec54f883e0cad2d73986640c1590eb9bfaaba7ad17394481e6e", size = 16645480, upload-time = "2026-03-29T13:19:03.63Z" },
    { url = "https://files.pythonhosted.org/packages/34/49/f2312c154b82a286758ee2f1743336d50651f8b5195db18cdb63675ff649/numpy-2.4.4-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:62d6b0f03b694173f9fcb1fb317f7222fd0b0b103e784c6549f5e53a27718c44", size = 17020036, upload-time = "2026-03-29T13:19:07.428Z" },
    { url = "https://files.pythonhosted.org/packages/7b/e9/736d17bd77f1b0ec4f9901aaec129c00d59f5d84d5e79bba540ef12c2330/numpy-2.4.4-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:fbc356aae7adf9e6336d336b9c8111d390a05df88f1805573ebb0807bd06fd1d", size = 18368643, upload-time = "2026-03-29T13:19:10.775Z" },
    { url = "https://files.pythonhosted.org/packages/63/f6/d417977c5f519b17c8a5c3bc9e8304b0908b0e21136fe43bf628a1343914/numpy-2.4.4-cp312-cp312-win32.whl", hash = "sha256:0d35aea54ad1d420c812bfa0385c71cd7cc5bcf7c65fed95fc2cd02fe8c79827", size = 5961117, upload-time = "2026-03-29T13:19:13.464Z" },
    { url = "https://files.pythonhosted.org/packages/2d/5b/e1deebf88ff431b01b7406ca3583ab2bbb90972bbe1c568732e49c844f7e/numpy-2.4.4-cp312-cp312-win_amd64.whl", hash = "sha256:b5f0362dc928a6ecd9db58868fca5e48485205e3855957bdedea308f8672ea4a", size = 12320584, upload-time = "2026-03-29T13:19:16.155Z" },
    { url = "https://files.pythonhosted.org/packages/58/89/e4e856ac82a68c3ed64486a544977d0e7bdd18b8da75b78a577ca31c4395/numpy-2.4.4-cp312-cp312-win_arm64.whl", hash = "sha256:846300f379b5b12cc769334464656bc882e0735d27d9726568bc932fdc49d5ec", size = 10221450, upload-time = "2026-03-29T13:19:18.994Z" },
    { url = "https://files.pythonhosted.org/packages/14/1d/d0a583ce4fefcc3308806a749a536c201ed6b5ad6e1322e227ee4848979d/numpy-2.4.4-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:08f2e31ed5e6f04b118e49821397f12767934cfdd12a1ce86a058f91e004ee50", size = 16684933, upload-time = "2026-03-29T13:19:22.47Z" },
    { url = "https://files.pythonhosted.org/packages/c1/62/2b7a48fbb745d344742c0277f01286dead15f3f68e4f359fbfcf7b48f70f/numpy-2.4.4-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:e823b8b6edc81e747526f70f71a9c0a07ac4e7ad13020aa736bb7c9d67196115", size = 14694532, upload-time = "2026-03-29T13:19:25.581Z" },
    { url = "https://files.pythonhosted.org/packages/e5/87/499737bfba066b4a3bebff24a8f1c5b2dee410b209bc6668c9be692580f0/numpy-2.4.4-cp313-cp313-macosx_14_0_arm64.whl", hash = "sha256:4a19d9dba1a76618dd86b164d608566f393f8ec6ac7c44f0cc879011c45e65af", size = 5199661, upload-time = "2026-03-29T13:19:28.31Z" },
    { url = "https://files.pythonhosted.org/packages/cd/da/464d551604320d1491bc345efed99b4b7034143a85787aab78d5691d5a0e/numpy-2.4.4-cp313-cp313-macosx_14_0_x86_64.whl", hash = "sha256:d2a8490669bfe99a233298348acc2d824d496dee0e66e31b66a6022c2ad74a5c", size = 6547539, upload-time = "2026-03-29T13:19:30.97Z" },
    { url = "https://files.pythonhosted.org/packages/7d/90/8d23e3b0dafd024bf31bdec225b3bb5c2dbfa6912f8a53b8659f21216cbf/numpy-2.4.4-cp313-cp313-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:45dbed2ab436a9e826e302fcdcbe9133f9b0006e5af7168afb8963a6520da103", size = 15668806, upload-time = "2026-03-29T13:19:33.887Z" },
    { url = "https://files.pythonhosted.org/packages/d1/73/a9d864e42a01896bb5974475438f16086be9ba1f0d19d0bb7a07427c4a8b/numpy-2.4.4-cp313-cp313-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:c901b15172510173f5cb310eae652908340f8dede90fff9e3bf6c0d8dfd92f83", size = 16632682, upload-time = "2026-03-29T13:19:37.336Z" },
    { url = "https://files.pythonhosted.org/packages/34/fb/14570d65c3bde4e202a031210475ae9cde9b7686a2e7dc97ee67d2833b35/numpy-2.4.4-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:99d838547ace2c4aace6c4f76e879ddfe02bb58a80c1549928477862b7a6d6ed", size = 17019810, upload-time = "2026-03-29T13:19:40.963Z" },
    { url = "https://files.pythonhosted.org/packages/8a/77/2ba9d87081fd41f6d640c83f26fb7351e536b7ce6dd9061b6af5904e8e46/numpy-2.4.4-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:0aec54fd785890ecca25a6003fd9a5aed47ad607bbac5cd64f836ad8666f4959", size = 18357394, upload-time = "2026-03-29T13:19:44.859Z" },
    { url = "https://files.pythonhosted.org/packages/a2/23/52666c9a41708b0853fa3b1a12c90da38c507a3074883823126d4e9d5b30/numpy-2.4.4-cp313-cp313-win32.whl", hash = "sha256:07077278157d02f65c43b1b26a3886bce886f95d20aabd11f87932750dfb14ed", size = 5959556, upload-time = "2026-03-29T13:19:47.661Z" },
    { url = "https://files.pythonhosted.org/packages/57/fb/48649b4971cde70d817cf97a2a2fdc0b4d8308569f1dd2f2611959d2e0cf/numpy-2.4.4-cp313-cp313-win_amd64.whl", hash = "sha256:5c70f1cc1c4efbe316a572e2d8b9b9cc44e89b95f79ca3331553fbb63716e2bf", size = 12317311, upload-time = "2026-03-29T13:19:50.67Z" },
    { url = "https://files.pythonhosted.org/packages/ba/d8/11490cddd564eb4de97b4579ef6bfe6a736cc07e94c1598590ae25415e01/numpy-2.4.4-cp313-cp313-win_arm64.whl", hash = "sha256:ef4059d6e5152fa1a39f888e344c73fdc926e1b2dd58c771d67b0acfbf2aa67d", size = 10222060, upload-time = "2026-03-29T13:19:54.229Z" },
    { url = "https://files.pythonhosted.org/packages/99/5d/dab4339177a905aad3e2221c915b35202f1ec30d750dd2e5e9d9a72b804b/numpy-2.4.4-cp313-cp313t-macosx_11_0_arm64.whl", hash = "sha256:4bbc7f303d125971f60ec0aaad5e12c62d0d2c925f0ab1273debd0e4ba37aba5", size = 14822302, upload-time = "2026-03-29T13:19:57.585Z" },
    { url = "https://files.pythonhosted.org/packages/eb/e4/0564a65e7d3d97562ed6f9b0fd0fb0a6f559ee444092f105938b50043876/numpy-2.4.4-cp313-cp313t-macosx_14_0_arm64.whl", hash = "sha256:4d6d57903571f86180eb98f8f0c839fa9ebbfb031356d87f1361be91e433f5b7", size = 5327407, upload-time = "2026-03-29T13:20:00.601Z" },
    { url = "https://files.pythonhosted.org/packages/29/8d/35a3a6ce5ad371afa58b4700f1c820f8f279948cca32524e0a695b0ded83/numpy-2.4.4-cp313-cp313t-macosx_14_0_x86_64.whl", hash = "sha256:4636de7fd195197b7535f231b5de9e4b36d2c440b6e566d2e4e4746e6af0ca93", size = 6647631, upload-time = "2026-03-29T13:20:02.855Z" },
    { url = "https://files.pythonhosted.org/packages/f4/da/477731acbd5a58a946c736edfdabb2ac5b34c3d08d1ba1a7b437fa0884df/numpy-2.4.4-cp313-cp313t-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:ad2e2ef14e0b04e544ea2fa0a36463f847f113d314aa02e5b402fdf910ef309e", size = 15727691, upload-time = "2026-03-29T13:20:06.004Z" },
    { url = "https://files.pythonhosted.org/packages/e6/db/338535d9b152beabeb511579598418ba0212ce77cf9718edd70262cc4370/numpy-2.4.4-cp313-cp313t-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:5a285b3b96f951841799528cd1f4f01cd70e7e0204b4abebac9463eecfcf2a40", size = 16681241, upload-time = "2026-03-29T13:20:09.417Z" },
    { url = "https://files.pythonhosted.org/packages/e2/a9/ad248e8f58beb7a0219b413c9c7d8151c5d285f7f946c3e26695bdbbe2df/numpy-2.4.4-cp313-cp313t-musllinux_1_2_aarch64.whl", hash = "sha256:f8474c4241bc18b750be2abea9d7a9ec84f46ef861dbacf86a4f6e043401f79e", size = 17085767, upload-time = "2026-03-29T13:20:13.126Z" },
    { url = "https://files.pythonhosted.org/packages/b5/1a/3b88ccd3694681356f70da841630e4725a7264d6a885c8d442a697e1146b/numpy-2.4.4-cp313-cp313t-musllinux_1_2_x86_64.whl", hash = "sha256:4e874c976154687c1f71715b034739b45c7711bec81db01914770373d125e392", size = 18403169, upload-time = "2026-03-29T13:20:17.096Z" },
    { url = "https://files.pythonhosted.org/packages/c2/c9/fcfd5d0639222c6eac7f304829b04892ef51c96a75d479214d77e3ce6e33/numpy-2.4.4-cp313-cp313t-win32.whl", hash = "sha256:9c585a1790d5436a5374bac930dad6ed244c046ed91b2b2a3634eb2971d21008", size = 6083477, upload-time = "2026-03-29T13:20:20.195Z" },
    { url = "https://files.pythonhosted.org/packages/d5/e3/3938a61d1c538aaec8ed6fd6323f57b0c2d2d2219512434c5c878db76553/numpy-2.4.4-cp313-cp313t-win_amd64.whl", hash = "sha256:93e15038125dc1e5345d9b5b68aa7f996ec33b98118d18c6ca0d0b7d6198b7e8", size = 12457487, upload-time = "2026-03-29T13:20:22.946Z" },
    { url = "https://files.pythonhosted.org/packages/97/6a/7e345032cc60501721ef94e0e30b60f6b0bd601f9174ebd36389a2b86d40/numpy-2.4.4-cp313-cp313t-win_arm64.whl", hash = "sha256:0dfd3f9d3adbe2920b68b5cd3d51444e13a10792ec7154cd0a2f6e74d4ab3233", size = 10292002, upload-time = "2026-03-29T13:20:25.909Z" },
    { url = "https://files.pythonhosted.org/packages/6e/06/c54062f85f673dd5c04cbe2f14c3acb8c8b95e3384869bb8cc9bff8cb9df/numpy-2.4.4-cp314-cp314-macosx_10_15_x86_64.whl", hash = "sha256:f169b9a863d34f5d11b8698ead99febeaa17a13ca044961aa8e2662a6c7766a0", size = 16684353, upload-time = "2026-03-29T13:20:29.504Z" },
    { url = "https://files.pythonhosted.org/packages/4c/39/8a320264a84404c74cc7e79715de85d6130fa07a0898f67fb5cd5bd79908/numpy-2.4.4-cp314-cp314-macosx_11_0_arm64.whl", hash = "sha256:2483e4584a1cb3092da4470b38866634bafb223cbcd551ee047633fd2584599a", size = 14704914, upload-time = "2026-03-29T13:20:33.547Z" },
    { url = "https://files.pythonhosted.org/packages/91/fb/287076b2614e1d1044235f50f03748f31fa287e3dbe6abeb35cdfa351eca/numpy-2.4.4-cp314-cp314-macosx_14_0_arm64.whl", hash = "sha256:2d19e6e2095506d1736b7d80595e0f252d76b89f5e715c35e06e937679ea7d7a", size = 5210005, upload-time = "2026-03-29T13:20:36.45Z" },
    { url = "https://files.pythonhosted.org/packages/63/eb/fcc338595309910de6ecabfcef2419a9ce24399680bfb149421fa2df1280/numpy-2.4.4-cp314-cp314-macosx_14_0_x86_64.whl", hash = "sha256:6a246d5914aa1c820c9443ddcee9c02bec3e203b0c080349533fae17727dfd1b", size = 6544974, upload-time = "2026-03-29T13:20:39.014Z" },
    { url = "https://files.pythonhosted.org/packages/44/5d/e7e9044032a716cdfaa3fba27a8e874bf1c5f1912a1ddd4ed071bf8a14a6/numpy-2.4.4-cp314-cp314-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:989824e9faf85f96ec9c7761cd8d29c531ad857bfa1daa930cba85baaecf1a9a", size = 15684591, upload-time = "2026-03-29T13:20:42.146Z" },
    { url = "https://files.pythonhosted.org/packages/98/7c/21252050676612625449b4807d6b695b9ce8a7c9e1c197ee6216c8a65c7c/numpy-2.4.4-cp314-cp314-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:27a8d92cd10f1382a67d7cf4db7ce18341b66438bdd9f691d7b0e48d104c2a9d", size = 16637700, upload-time = "2026-03-29T13:20:46.204Z" },
    { url = "https://files.pythonhosted.org/packages/b1/29/56d2bbef9465db24ef25393383d761a1af4f446a1df9b8cded4fe3a5a5d7/numpy-2.4.4-cp314-cp314-musllinux_1_2_aarch64.whl", hash = "sha256:e44319a2953c738205bf3354537979eaa3998ed673395b964c1176083dd46252", size = 17035781, upload-time = "2026-03-29T13:20:50.242Z" },
    { url = "https://files.pythonhosted.org/packages/e3/2b/a35a6d7589d21f44cea7d0a98de5ddcbb3d421b2622a5c96b1edf18707c3/numpy-2.4.4-cp314-cp314-musllinux_1_2_x86_64.whl", hash = "sha256:e892aff75639bbef0d2a2cfd55535510df26ff92f63c92cd84ef8d4ba5a5557f", size = 18362959, upload-time = "2026-03-29T13:20:54.019Z" },
    { url = "https://files.pythonhosted.org/packages/64/c9/d52ec581f2390e0f5f85cbfd80fb83d965fc15e9f0e1aec2195faa142cde/numpy-2.4.4-cp314-cp314-win32.whl", hash = "sha256:1378871da56ca8943c2ba674530924bb8ca40cd228358a3b5f302ad60cf875fc", size = 6008768, upload-time = "2026-03-29T13:20:56.912Z" },
    { url = "https://files.pythonhosted.org/packages/fa/22/4cc31a62a6c7b74a8730e31a4274c5dc80e005751e277a2ce38e675e4923/numpy-2.4.4-cp314-cp314-win_amd64.whl", hash = "sha256:715d1c092715954784bc79e1174fc2a90093dc4dc84ea15eb14dad8abdcdeb74", size = 12449181, upload-time = "2026-03-29T13:20:59.548Z" },
    { url = "https://files.pythonhosted.org/packages/70/2e/14cda6f4d8e396c612d1bf97f22958e92148801d7e4f110cabebdc0eef4b/numpy-2.4.4-cp314-cp314-win_arm64.whl", hash = "sha256:2c194dd721e54ecad9ad387c1d35e63dce5c4450c6dc7dd5611283dda239aabb", size = 10496035, upload-time = "2026-03-29T13:21:02.524Z" },
    { url = "https://files.pythonhosted.org/packages/b1/e8/8fed8c8d848d7ecea092dc3469643f9d10bc3a134a815a3b033da1d2039b/numpy-2.4.4-cp314-cp314t-macosx_11_0_arm64.whl", hash = "sha256:2aa0613a5177c264ff5921051a5719d20095ea586ca88cc802c5c218d1c67d3e", size = 14824958, upload-time = "2026-03-29T13:21:05.671Z" },
    { url = "https://files.pythonhosted.org/packages/05/1a/d8007a5138c179c2bf33ef44503e83d70434d2642877ee8fbb230e7c0548/numpy-2.4.4-cp314-cp314t-macosx_14_0_arm64.whl", hash = "sha256:42c16925aa5a02362f986765f9ebabf20de75cdefdca827d14315c568dcab113", size = 5330020, upload-time = "2026-03-29T13:21:08.635Z" },
    { url = "https://files.pythonhosted.org/packages/99/64/ffb99ac6ae93faf117bcbd5c7ba48a7f45364a33e8e458545d3633615dda/numpy-2.4.4-cp314-cp314t-macosx_14_0_x86_64.whl", hash = "sha256:874f200b2a981c647340f841730fc3a2b54c9d940566a3c4149099591e2c4c3d", size = 6650758, upload-time = "2026-03-29T13:21:10.949Z" },
    { url = "https://files.pythonhosted.org/packages/6e/6e/795cc078b78a384052e73b2f6281ff7a700e9bf53bcce2ee579d4f6dd879/numpy-2.4.4-cp314-cp314t-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:c9b39d38a9bd2ae1becd7eac1303d031c5c110ad31f2b319c6e7d98b135c934d", size = 15729948, upload-time = "2026-03-29T13:21:14.047Z" },
    { url = "https://files.pythonhosted.org/packages/5f/86/2acbda8cc2af5f3d7bfc791192863b9e3e19674da7b5e533fded124d1299/numpy-2.4.4-cp314-cp314t-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:b268594bccac7d7cf5844c7732e3f20c50921d94e36d7ec9b79e9857694b1b2f", size = 16679325, upload-time = "2026-03-29T13:21:17.561Z" },
    { url = "https://files.pythonhosted.org/packages/bc/59/cafd83018f4aa55e0ac6fa92aa066c0a1877b77a615ceff1711c260ffae8/numpy-2.4.4-cp314-cp314t-musllinux_1_2_aarch64.whl", hash = "sha256:ac6b31e35612a26483e20750126d30d0941f949426974cace8e6b5c58a3657b0", size = 17084883, upload-time = "2026-03-29T13:21:21.106Z" },
    { url = "https://files.pythonhosted.org/packages/f0/85/a42548db84e65ece46ab2caea3d3f78b416a47af387fcbb47ec28e660dc2/numpy-2.4.4-cp314-cp314t-musllinux_1_2_x86_64.whl", hash = "sha256:8e3ed142f2728df44263aaf5fb1f5b0b99f4070c553a0d7f033be65338329150", size = 18403474, upload-time = "2026-03-29T13:21:24.828Z" },
    { url = "https://files.pythonhosted.org/packages/ed/ad/483d9e262f4b831000062e5d8a45e342166ec8aaa1195264982bca267e62/numpy-2.4.4-cp314-cp314t-win32.whl", hash = "sha256:dddbbd259598d7240b18c9d87c56a9d2fb3b02fe266f49a7c101532e78c1d871", size = 6155500, upload-time = "2026-03-29T13:21:28.205Z" },
    { url = "https://files.pythonhosted.org/packages/c7/03/2fc4e14c7bd4ff2964b74ba90ecb8552540b6315f201df70f137faa5c589/numpy-2.4.4-cp314-cp314t-win_amd64.whl", hash = "sha256:a7164afb23be6e37ad90b2f10426149fd75aee07ca55653d2aa41e66c4ef697e", size = 12637755, upload-time = "2026-03-29T13:21:31.107Z" },
    { url = "https://files.pythonhosted.org/packages/58/78/548fb8e07b1a341746bfbecb32f2c268470f45fa028aacdbd10d9bc73aab/numpy-2.4.4-cp314-cp314t-win_arm64.whl", hash = "sha256:ba203255017337d39f89bdd58417f03c4426f12beed0440cfd933cb15f8669c7", size = 10566643, upload-time = "2026-03-29T13:21:34.339Z" },
]

[[package]]
name = "packaging"
version = "26.2"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/d7/f1/e7a6dd94a8d4a5626c03e4e99c87f241ba9e350cd9e6d75123f992427270/packaging-26.2.tar.gz", hash = "sha256:ff452ff5a3e828ce110190feff1178bb1f2ea2281fa2075aadb987c2fb221661", size = 228134, upload-time = "2026-04-24T20:15:23.917Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/df/b2/87e62e8c3e2f4b32e5fe99e0b86d576da1312593b39f47d8ceef365e95ed/packaging-26.2-py3-none-any.whl", hash = "sha256:5fc45236b9446107ff2415ce77c807cee2862cb6fac22b8a73826d0693b0980e", size = 100195, upload-time = "2026-04-24T20:15:22.081Z" },
]

[[package]]
name = "pandas"
version = "3.0.2"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "numpy" },
    { name = "python-dateutil" },
    { name = "tzdata", marker = "sys_platform == 'emscripten' or sys_platform == 'win32'" },
]
sdist = { url = "https://files.pythonhosted.org/packages/da/99/b342345300f13440fe9fe385c3c481e2d9a595ee3bab4d3219247ac94e9a/pandas-3.0.2.tar.gz", hash = "sha256:f4753e73e34c8d83221ba58f232433fca2748be8b18dbca02d242ed153945043", size = 4645855, upload-time = "2026-03-31T06:48:30.816Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/f3/b0/c20bd4d6d3f736e6bd6b55794e9cd0a617b858eaad27c8f410ea05d953b7/pandas-3.0.2-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:232a70ebb568c0c4d2db4584f338c1577d81e3af63292208d615907b698a0f18", size = 10347921, upload-time = "2026-03-31T06:46:33.36Z" },
    { url = "https://files.pythonhosted.org/packages/35/d0/4831af68ce30cc2d03c697bea8450e3225a835ef497d0d70f31b8cdde965/pandas-3.0.2-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:970762605cff1ca0d3f71ed4f3a769ea8f85fc8e6348f6e110b8fea7e6eb5a14", size = 9888127, upload-time = "2026-03-31T06:46:36.253Z" },
    { url = "https://files.pythonhosted.org/packages/61/a9/16ea9346e1fc4a96e2896242d9bc674764fb9049b0044c0132502f7a771e/pandas-3.0.2-cp312-cp312-manylinux_2_24_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:aff4e6f4d722e0652707d7bcb190c445fe58428500c6d16005b02401764b1b3d", size = 10399577, upload-time = "2026-03-31T06:46:39.224Z" },
    { url = "https://files.pythonhosted.org/packages/c4/a8/3a61a721472959ab0ce865ef05d10b0d6bfe27ce8801c99f33d4fa996e65/pandas-3.0.2-cp312-cp312-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:ef8b27695c3d3dc78403c9a7d5e59a62d5464a7e1123b4e0042763f7104dc74f", size = 10880030, upload-time = "2026-03-31T06:46:42.412Z" },
    { url = "https://files.pythonhosted.org/packages/da/65/7225c0ea4d6ce9cb2160a7fb7f39804871049f016e74782e5dade4d14109/pandas-3.0.2-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:f8d68083e49e16b84734eb1a4dcae4259a75c90fb6e2251ab9a00b61120c06ab", size = 11409468, upload-time = "2026-03-31T06:46:45.2Z" },
    { url = "https://files.pythonhosted.org/packages/fa/5b/46e7c76032639f2132359b5cf4c785dd8cf9aea5ea64699eac752f02b9db/pandas-3.0.2-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:32cc41f310ebd4a296d93515fcac312216adfedb1894e879303987b8f1e2b97d", size = 11936381, upload-time = "2026-03-31T06:46:48.293Z" },
    { url = "https://files.pythonhosted.org/packages/7b/8b/721a9cff6fa6a91b162eb51019c6243b82b3226c71bb6c8ef4a9bd65cbc6/pandas-3.0.2-cp312-cp312-win_amd64.whl", hash = "sha256:a4785e1d6547d8427c5208b748ae2efb64659a21bd82bf440d4262d02bfa02a4", size = 9744993, upload-time = "2026-03-31T06:46:51.488Z" },
    { url = "https://files.pythonhosted.org/packages/d5/18/7f0bd34ae27b28159aa80f2a6799f47fda34f7fb938a76e20c7b7fe3b200/pandas-3.0.2-cp312-cp312-win_arm64.whl", hash = "sha256:08504503f7101300107ecdc8df73658e4347586db5cfdadabc1592e9d7e7a0fd", size = 9056118, upload-time = "2026-03-31T06:46:54.548Z" },
    { url = "https://files.pythonhosted.org/packages/bf/ca/3e639a1ea6fcd0617ca4e8ca45f62a74de33a56ae6cd552735470b22c8d3/pandas-3.0.2-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:b5918ba197c951dec132b0c5929a00c0bf05d5942f590d3c10a807f6e15a57d3", size = 10321105, upload-time = "2026-03-31T06:46:57.327Z" },
    { url = "https://files.pythonhosted.org/packages/0b/77/dbc82ff2fb0e63c6564356682bf201edff0ba16c98630d21a1fb312a8182/pandas-3.0.2-cp313-cp313-macosx_11_0_arm64.whl", hash = "sha256:d606a041c89c0a474a4702d532ab7e73a14fe35c8d427b972a625c8e46373668", size = 9864088, upload-time = "2026-03-31T06:46:59.935Z" },
    { url = "https://files.pythonhosted.org/packages/5c/2b/341f1b04bbca2e17e13cd3f08c215b70ef2c60c5356ef1e8c6857449edc7/pandas-3.0.2-cp313-cp313-manylinux_2_24_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:710246ba0616e86891b58ab95f2495143bb2bc83ab6b06747c74216f583a6ac9", size = 10369066, upload-time = "2026-03-31T06:47:02.792Z" },
    { url = "https://files.pythonhosted.org/packages/12/c5/cbb1ffefb20a93d3f0e1fdcda699fb84976210d411b008f97f48bf6ce27e/pandas-3.0.2-cp313-cp313-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:5d3cfe227c725b1f3dff4278b43d8c784656a42a9325b63af6b1492a8232209e", size = 10876780, upload-time = "2026-03-31T06:47:06.205Z" },
    { url = "https://files.pythonhosted.org/packages/98/fe/2249ae5e0a69bd0ddf17353d0a5d26611d70970111f5b3600cdc8be883e7/pandas-3.0.2-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:c3b723df9087a9a9a840e263ebd9f88b64a12075d1bf2ea401a5a42f254f084d", size = 11375181, upload-time = "2026-03-31T06:47:09.383Z" },
    { url = "https://files.pythonhosted.org/packages/de/64/77a38b09e70b6464883b8d7584ab543e748e42c1b5d337a2ee088e0df741/pandas-3.0.2-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:a3096110bf9eac0070b7208465f2740e2d8a670d5cb6530b5bb884eca495fd39", size = 11928899, upload-time = "2026-03-31T06:47:12.686Z" },
    { url = "https://files.pythonhosted.org/packages/5e/52/42855bf626868413f761addd574acc6195880ae247a5346477a4361c3acb/pandas-3.0.2-cp313-cp313-win_amd64.whl", hash = "sha256:07a10f5c36512eead51bc578eb3354ad17578b22c013d89a796ab5eee90cd991", size = 9746574, upload-time = "2026-03-31T06:47:15.64Z" },
    { url = "https://files.pythonhosted.org/packages/88/39/21304ae06a25e8bf9fc820d69b29b2c495b2ae580d1e143146c309941760/pandas-3.0.2-cp313-cp313-win_arm64.whl", hash = "sha256:5fdbfa05931071aba28b408e59226186b01eb5e92bea2ab78b65863ca3228d84", size = 9047156, upload-time = "2026-03-31T06:47:18.595Z" },
    { url = "https://files.pythonhosted.org/packages/72/20/7defa8b27d4f330a903bb68eea33be07d839c5ea6bdda54174efcec0e1d2/pandas-3.0.2-cp313-cp313t-macosx_10_13_x86_64.whl", hash = "sha256:dbc20dea3b9e27d0e66d74c42b2d0c1bed9c2ffe92adea33633e3bedeb5ac235", size = 10756238, upload-time = "2026-03-31T06:47:22.012Z" },
    { url = "https://files.pythonhosted.org/packages/e9/95/49433c14862c636afc0e9b2db83ff16b3ad92959364e52b2955e44c8e94c/pandas-3.0.2-cp313-cp313t-macosx_11_0_arm64.whl", hash = "sha256:b75c347eff42497452116ce05ef461822d97ce5b9ff8df6edacb8076092c855d", size = 10408520, upload-time = "2026-03-31T06:47:25.197Z" },
    { url = "https://files.pythonhosted.org/packages/3b/f8/462ad2b5881d6b8ec8e5f7ed2ea1893faa02290d13870a1600fe72ad8efc/pandas-3.0.2-cp313-cp313t-manylinux_2_24_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:d1478075142e83a5571782ad007fb201ed074bdeac7ebcc8890c71442e96adf7", size = 10324154, upload-time = "2026-03-31T06:47:28.097Z" },
    { url = "https://files.pythonhosted.org/packages/0a/65/d1e69b649cbcddda23ad6e4c40ef935340f6f652a006e5cbc3555ac8adb3/pandas-3.0.2-cp313-cp313t-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:5880314e69e763d4c8b27937090de570f1fb8d027059a7ada3f7f8e98bdcb677", size = 10714449, upload-time = "2026-03-31T06:47:30.85Z" },
    { url = "https://files.pythonhosted.org/packages/47/a4/85b59bc65b8190ea3689882db6cdf32a5003c0ccd5a586c30fdcc3ffc4fc/pandas-3.0.2-cp313-cp313t-musllinux_1_2_aarch64.whl", hash = "sha256:b5329e26898896f06035241a626d7c335daa479b9bbc82be7c2742d048e41172", size = 11338475, upload-time = "2026-03-31T06:47:34.026Z" },
    { url = "https://files.pythonhosted.org/packages/1e/c4/bc6966c6e38e5d9478b935272d124d80a589511ed1612a5d21d36f664c68/pandas-3.0.2-cp313-cp313t-musllinux_1_2_x86_64.whl", hash = "sha256:81526c4afd31971f8b62671442a4b2b51e0aa9acc3819c9f0f12a28b6fcf85f1", size = 11786568, upload-time = "2026-03-31T06:47:36.941Z" },
    { url = "https://files.pythonhosted.org/packages/e8/74/09298ca9740beed1d3504e073d67e128aa07e5ca5ca2824b0c674c0b8676/pandas-3.0.2-cp313-cp313t-win_amd64.whl", hash = "sha256:7cadd7e9a44ec13b621aec60f9150e744cfc7a3dd32924a7e2f45edff31823b0", size = 10488652, upload-time = "2026-03-31T06:47:40.612Z" },
    { url = "https://files.pythonhosted.org/packages/bb/40/c6ea527147c73b24fc15c891c3fcffe9c019793119c5742b8784a062c7db/pandas-3.0.2-cp314-cp314-macosx_10_15_x86_64.whl", hash = "sha256:db0dbfd2a6cdf3770aa60464d50333d8f3d9165b2f2671bcc299b72de5a6677b", size = 10326084, upload-time = "2026-03-31T06:47:43.834Z" },
    { url = "https://files.pythonhosted.org/packages/95/25/bdb9326c3b5455f8d4d3549fce7abcf967259de146fe2cf7a82368141948/pandas-3.0.2-cp314-cp314-macosx_11_0_arm64.whl", hash = "sha256:0555c5882688a39317179ab4a0ed41d3ebc8812ab14c69364bbee8fb7a3f6288", size = 9914146, upload-time = "2026-03-31T06:47:46.67Z" },
    { url = "https://files.pythonhosted.org/packages/8d/77/3a227ff3337aa376c60d288e1d61c5d097131d0ac71f954d90a8f369e422/pandas-3.0.2-cp314-cp314-manylinux_2_24_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:01f31a546acd5574ef77fe199bc90b55527c225c20ccda6601cf6b0fd5ed597c", size = 10444081, upload-time = "2026-03-31T06:47:49.681Z" },
    { url = "https://files.pythonhosted.org/packages/15/88/3cdd54fa279341afa10acf8d2b503556b1375245dccc9315659f795dd2e9/pandas-3.0.2-cp314-cp314-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:deeca1b5a931fdf0c2212c8a659ade6d3b1edc21f0914ce71ef24456ca7a6535", size = 10897535, upload-time = "2026-03-31T06:47:53.033Z" },
    { url = "https://files.pythonhosted.org/packages/06/9d/98cc7a7624f7932e40f434299260e2917b090a579d75937cb8a57b9d2de3/pandas-3.0.2-cp314-cp314-musllinux_1_2_aarch64.whl", hash = "sha256:0f48afd9bb13300ffb5a3316973324c787054ba6665cda0da3fbd67f451995db", size = 11446992, upload-time = "2026-03-31T06:47:56.193Z" },
    { url = "https://files.pythonhosted.org/packages/9a/cd/19ff605cc3760e80602e6826ddef2824d8e7050ed80f2e11c4b079741dc3/pandas-3.0.2-cp314-cp314-musllinux_1_2_x86_64.whl", hash = "sha256:6c4d8458b97a35717b62469a4ea0e85abd5ed8687277f5ccfc67f8a5126f8c53", size = 11968257, upload-time = "2026-03-31T06:47:59.137Z" },
    { url = "https://files.pythonhosted.org/packages/db/60/aba6a38de456e7341285102bede27514795c1eaa353bc0e7638b6b785356/pandas-3.0.2-cp314-cp314-win_amd64.whl", hash = "sha256:b35d14bb5d8285d9494fe93815a9e9307c0876e10f1e8e89ac5b88f728ec8dcf", size = 9865893, upload-time = "2026-03-31T06:48:02.038Z" },
    { url = "https://files.pythonhosted.org/packages/08/71/e5ec979dd2e8a093dacb8864598c0ff59a0cee0bbcdc0bfec16a51684d4f/pandas-3.0.2-cp314-cp314-win_arm64.whl", hash = "sha256:63d141b56ef686f7f0d714cfb8de4e320475b86bf4b620aa0b7da89af8cbdbbb", size = 9188644, upload-time = "2026-03-31T06:48:05.045Z" },
    { url = "https://files.pythonhosted.org/packages/f1/6c/7b45d85db19cae1eb524f2418ceaa9d85965dcf7b764ed151386b7c540f0/pandas-3.0.2-cp314-cp314t-macosx_10_15_x86_64.whl", hash = "sha256:140f0cffb1fa2524e874dde5b477d9defe10780d8e9e220d259b2c0874c89d9d", size = 10776246, upload-time = "2026-03-31T06:48:07.789Z" },
    { url = "https://files.pythonhosted.org/packages/a8/3e/7b00648b086c106e81766f25322b48aa8dfa95b55e621dbdf2fdd413a117/pandas-3.0.2-cp314-cp314t-macosx_11_0_arm64.whl", hash = "sha256:ae37e833ff4fed0ba352f6bdd8b73ba3ab3256a85e54edfd1ab51ae40cca0af8", size = 10424801, upload-time = "2026-03-31T06:48:10.897Z" },
    { url = "https://files.pythonhosted.org/packages/da/6e/558dd09a71b53b4008e7fc8a98ec6d447e9bfb63cdaeea10e5eb9b2dabe8/pandas-3.0.2-cp314-cp314t-manylinux_2_24_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:4d888a5c678a419a5bb41a2a93818e8ed9fd3172246555c0b37b7cc27027effd", size = 10345643, upload-time = "2026-03-31T06:48:13.7Z" },
    { url = "https://files.pythonhosted.org/packages/be/e3/921c93b4d9a280409451dc8d07b062b503bbec0531d2627e73a756e99a82/pandas-3.0.2-cp314-cp314t-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:b444dc64c079e84df91baa8bf613d58405645461cabca929d9178f2cd392398d", size = 10743641, upload-time = "2026-03-31T06:48:16.659Z" },
    { url = "https://files.pythonhosted.org/packages/56/ca/fd17286f24fa3b4d067965d8d5d7e14fe557dd4f979a0b068ac0deaf8228/pandas-3.0.2-cp314-cp314t-musllinux_1_2_aarch64.whl", hash = "sha256:4544c7a54920de8eeacaa1466a6b7268ecfbc9bc64ab4dbb89c6bbe94d5e0660", size = 11361993, upload-time = "2026-03-31T06:48:19.475Z" },
    { url = "https://files.pythonhosted.org/packages/e4/a5/2f6ed612056819de445a433ca1f2821ac3dab7f150d569a59e9cc105de1d/pandas-3.0.2-cp314-cp314t-musllinux_1_2_x86_64.whl", hash = "sha256:734be7551687c00fbd760dc0522ed974f82ad230d4a10f54bf51b80d44a08702", size = 11815274, upload-time = "2026-03-31T06:48:22.695Z" },
    { url = "https://files.pythonhosted.org/packages/00/2f/b622683e99ec3ce00b0854bac9e80868592c5b051733f2cf3a868e5fea26/pandas-3.0.2-cp314-cp314t-win_amd64.whl", hash = "sha256:57a07209bebcbcf768d2d13c9b78b852f9a15978dac41b9e6421a81ad4cdd276", size = 10888530, upload-time = "2026-03-31T06:48:25.806Z" },
    { url = "https://files.pythonhosted.org/packages/cb/2b/f8434233fab2bd66a02ec014febe4e5adced20e2693e0e90a07d118ed30e/pandas-3.0.2-cp314-cp314t-win_arm64.whl", hash = "sha256:5371b72c2d4d415d08765f32d689217a43227484e81b2305b52076e328f6f482", size = 9455341, upload-time = "2026-03-31T06:48:28.418Z" },
]

[[package]]
name = "parso"
version = "0.8.6"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/81/76/a1e769043c0c0c9fe391b702539d594731a4362334cdf4dc25d0c09761e7/parso-0.8.6.tar.gz", hash = "sha256:2b9a0332696df97d454fa67b81618fd69c35a7b90327cbe6ba5c92d2c68a7bfd", size = 401621, upload-time = "2026-02-09T15:45:24.425Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/b6/61/fae042894f4296ec49e3f193aff5d7c18440da9e48102c3315e1bc4519a7/parso-0.8.6-py2.py3-none-any.whl", hash = "sha256:2c549f800b70a5c4952197248825584cb00f033b29c692671d3bf08bf380baff", size = 106894, upload-time = "2026-02-09T15:45:21.391Z" },
]

[[package]]
name = "pexpect"
version = "4.9.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "ptyprocess", marker = "sys_platform != 'emscripten' and sys_platform != 'win32'" },
]
sdist = { url = "https://files.pythonhosted.org/packages/42/92/cc564bf6381ff43ce1f4d06852fc19a2f11d180f23dc32d9588bee2f149d/pexpect-4.9.0.tar.gz", hash = "sha256:ee7d41123f3c9911050ea2c2dac107568dc43b2d3b0c7557a33212c398ead30f", size = 166450, upload-time = "2023-11-25T09:07:26.339Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/9e/c3/059298687310d527a58bb01f3b1965787ee3b40dce76752eda8b44e9a2c5/pexpect-4.9.0-py2.py3-none-any.whl", hash = "sha256:7236d1e080e4936be2dc3e326cec0af72acf9212a7e1d060210e70a47e253523", size = 63772, upload-time = "2023-11-25T06:56:14.81Z" },
]

[[package]]
name = "platformdirs"
version = "4.9.6"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/9f/4a/0883b8e3802965322523f0b200ecf33d31f10991d0401162f4b23c698b42/platformdirs-4.9.6.tar.gz", hash = "sha256:3bfa75b0ad0db84096ae777218481852c0ebc6c727b3168c1b9e0118e458cf0a", size = 29400, upload-time = "2026-04-09T00:04:10.812Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/75/a6/a0a304dc33b49145b21f4808d763822111e67d1c3a32b524a1baf947b6e1/platformdirs-4.9.6-py3-none-any.whl", hash = "sha256:e61adb1d5e5cb3441b4b7710bea7e4c12250ca49439228cc1021c00dcfac0917", size = 21348, upload-time = "2026-04-09T00:04:09.463Z" },
]

[[package]]
name = "prompt-toolkit"
version = "3.0.52"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "wcwidth" },
]
sdist = { url = "https://files.pythonhosted.org/packages/a1/96/06e01a7b38dce6fe1db213e061a4602dd6032a8a97ef6c1a862537732421/prompt_toolkit-3.0.52.tar.gz", hash = "sha256:28cde192929c8e7321de85de1ddbe736f1375148b02f2e17edd840042b1be855", size = 434198, upload-time = "2025-08-27T15:24:02.057Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/84/03/0d3ce49e2505ae70cf43bc5bb3033955d2fc9f932163e84dc0779cc47f48/prompt_toolkit-3.0.52-py3-none-any.whl", hash = "sha256:9aac639a3bbd33284347de5ad8d68ecc044b91a762dc39b7c21095fcd6a19955", size = 391431, upload-time = "2025-08-27T15:23:59.498Z" },
]

[[package]]
name = "psutil"
version = "7.2.2"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/aa/c6/d1ddf4abb55e93cebc4f2ed8b5d6dbad109ecb8d63748dd2b20ab5e57ebe/psutil-7.2.2.tar.gz", hash = "sha256:0746f5f8d406af344fd547f1c8daa5f5c33dbc293bb8d6a16d80b4bb88f59372", size = 493740, upload-time = "2026-01-28T18:14:54.428Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/51/08/510cbdb69c25a96f4ae523f733cdc963ae654904e8db864c07585ef99875/psutil-7.2.2-cp313-cp313t-macosx_10_13_x86_64.whl", hash = "sha256:2edccc433cbfa046b980b0df0171cd25bcaeb3a68fe9022db0979e7aa74a826b", size = 130595, upload-time = "2026-01-28T18:14:57.293Z" },
    { url = "https://files.pythonhosted.org/packages/d6/f5/97baea3fe7a5a9af7436301f85490905379b1c6f2dd51fe3ecf24b4c5fbf/psutil-7.2.2-cp313-cp313t-macosx_11_0_arm64.whl", hash = "sha256:e78c8603dcd9a04c7364f1a3e670cea95d51ee865e4efb3556a3a63adef958ea", size = 131082, upload-time = "2026-01-28T18:14:59.732Z" },
    { url = "https://files.pythonhosted.org/packages/37/d6/246513fbf9fa174af531f28412297dd05241d97a75911ac8febefa1a53c6/psutil-7.2.2-cp313-cp313t-manylinux2010_x86_64.manylinux_2_12_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:1a571f2330c966c62aeda00dd24620425d4b0cc86881c89861fbc04549e5dc63", size = 181476, upload-time = "2026-01-28T18:15:01.884Z" },
    { url = "https://files.pythonhosted.org/packages/b8/b5/9182c9af3836cca61696dabe4fd1304e17bc56cb62f17439e1154f225dd3/psutil-7.2.2-cp313-cp313t-manylinux2014_aarch64.manylinux_2_17_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:917e891983ca3c1887b4ef36447b1e0873e70c933afc831c6b6da078ba474312", size = 184062, upload-time = "2026-01-28T18:15:04.436Z" },
    { url = "https://files.pythonhosted.org/packages/16/ba/0756dca669f5a9300d0cbcbfae9a4c30e446dfc7440ffe43ded5724bfd93/psutil-7.2.2-cp313-cp313t-win_amd64.whl", hash = "sha256:ab486563df44c17f5173621c7b198955bd6b613fb87c71c161f827d3fb149a9b", size = 139893, upload-time = "2026-01-28T18:15:06.378Z" },
    { url = "https://files.pythonhosted.org/packages/1c/61/8fa0e26f33623b49949346de05ec1ddaad02ed8ba64af45f40a147dbfa97/psutil-7.2.2-cp313-cp313t-win_arm64.whl", hash = "sha256:ae0aefdd8796a7737eccea863f80f81e468a1e4cf14d926bd9b6f5f2d5f90ca9", size = 135589, upload-time = "2026-01-28T18:15:08.03Z" },
    { url = "https://files.pythonhosted.org/packages/81/69/ef179ab5ca24f32acc1dac0c247fd6a13b501fd5534dbae0e05a1c48b66d/psutil-7.2.2-cp314-cp314t-macosx_10_15_x86_64.whl", hash = "sha256:eed63d3b4d62449571547b60578c5b2c4bcccc5387148db46e0c2313dad0ee00", size = 130664, upload-time = "2026-01-28T18:15:09.469Z" },
    { url = "https://files.pythonhosted.org/packages/7b/64/665248b557a236d3fa9efc378d60d95ef56dd0a490c2cd37dafc7660d4a9/psutil-7.2.2-cp314-cp314t-macosx_11_0_arm64.whl", hash = "sha256:7b6d09433a10592ce39b13d7be5a54fbac1d1228ed29abc880fb23df7cb694c9", size = 131087, upload-time = "2026-01-28T18:15:11.724Z" },
    { url = "https://files.pythonhosted.org/packages/d5/2e/e6782744700d6759ebce3043dcfa661fb61e2fb752b91cdeae9af12c2178/psutil-7.2.2-cp314-cp314t-manylinux2010_x86_64.manylinux_2_12_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:1fa4ecf83bcdf6e6c8f4449aff98eefb5d0604bf88cb883d7da3d8d2d909546a", size = 182383, upload-time = "2026-01-28T18:15:13.445Z" },
    { url = "https://files.pythonhosted.org/packages/57/49/0a41cefd10cb7505cdc04dab3eacf24c0c2cb158a998b8c7b1d27ee2c1f5/psutil-7.2.2-cp314-cp314t-manylinux2014_aarch64.manylinux_2_17_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:e452c464a02e7dc7822a05d25db4cde564444a67e58539a00f929c51eddda0cf", size = 185210, upload-time = "2026-01-28T18:15:16.002Z" },
    { url = "https://files.pythonhosted.org/packages/dd/2c/ff9bfb544f283ba5f83ba725a3c5fec6d6b10b8f27ac1dc641c473dc390d/psutil-7.2.2-cp314-cp314t-win_amd64.whl", hash = "sha256:c7663d4e37f13e884d13994247449e9f8f574bc4655d509c3b95e9ec9e2b9dc1", size = 141228, upload-time = "2026-01-28T18:15:18.385Z" },
    { url = "https://files.pythonhosted.org/packages/f2/fc/f8d9c31db14fcec13748d373e668bc3bed94d9077dbc17fb0eebc073233c/psutil-7.2.2-cp314-cp314t-win_arm64.whl", hash = "sha256:11fe5a4f613759764e79c65cf11ebdf26e33d6dd34336f8a337aa2996d71c841", size = 136284, upload-time = "2026-01-28T18:15:19.912Z" },
    { url = "https://files.pythonhosted.org/packages/e7/36/5ee6e05c9bd427237b11b3937ad82bb8ad2752d72c6969314590dd0c2f6e/psutil-7.2.2-cp36-abi3-macosx_10_9_x86_64.whl", hash = "sha256:ed0cace939114f62738d808fdcecd4c869222507e266e574799e9c0faa17d486", size = 129090, upload-time = "2026-01-28T18:15:22.168Z" },
    { url = "https://files.pythonhosted.org/packages/80/c4/f5af4c1ca8c1eeb2e92ccca14ce8effdeec651d5ab6053c589b074eda6e1/psutil-7.2.2-cp36-abi3-macosx_11_0_arm64.whl", hash = "sha256:1a7b04c10f32cc88ab39cbf606e117fd74721c831c98a27dc04578deb0c16979", size = 129859, upload-time = "2026-01-28T18:15:23.795Z" },
    { url = "https://files.pythonhosted.org/packages/b5/70/5d8df3b09e25bce090399cf48e452d25c935ab72dad19406c77f4e828045/psutil-7.2.2-cp36-abi3-manylinux2010_x86_64.manylinux_2_12_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:076a2d2f923fd4821644f5ba89f059523da90dc9014e85f8e45a5774ca5bc6f9", size = 155560, upload-time = "2026-01-28T18:15:25.976Z" },
    { url = "https://files.pythonhosted.org/packages/63/65/37648c0c158dc222aba51c089eb3bdfa238e621674dc42d48706e639204f/psutil-7.2.2-cp36-abi3-manylinux2014_aarch64.manylinux_2_17_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:b0726cecd84f9474419d67252add4ac0cd9811b04d61123054b9fb6f57df6e9e", size = 156997, upload-time = "2026-01-28T18:15:27.794Z" },
    { url = "https://files.pythonhosted.org/packages/8e/13/125093eadae863ce03c6ffdbae9929430d116a246ef69866dad94da3bfbc/psutil-7.2.2-cp36-abi3-musllinux_1_2_aarch64.whl", hash = "sha256:fd04ef36b4a6d599bbdb225dd1d3f51e00105f6d48a28f006da7f9822f2606d8", size = 148972, upload-time = "2026-01-28T18:15:29.342Z" },
    { url = "https://files.pythonhosted.org/packages/04/78/0acd37ca84ce3ddffaa92ef0f571e073faa6d8ff1f0559ab1272188ea2be/psutil-7.2.2-cp36-abi3-musllinux_1_2_x86_64.whl", hash = "sha256:b58fabe35e80b264a4e3bb23e6b96f9e45a3df7fb7eed419ac0e5947c61e47cc", size = 148266, upload-time = "2026-01-28T18:15:31.597Z" },
    { url = "https://files.pythonhosted.org/packages/b4/90/e2159492b5426be0c1fef7acba807a03511f97c5f86b3caeda6ad92351a7/psutil-7.2.2-cp37-abi3-win_amd64.whl", hash = "sha256:eb7e81434c8d223ec4a219b5fc1c47d0417b12be7ea866e24fb5ad6e84b3d988", size = 137737, upload-time = "2026-01-28T18:15:33.849Z" },
    { url = "https://files.pythonhosted.org/packages/8c/c7/7bb2e321574b10df20cbde462a94e2b71d05f9bbda251ef27d104668306a/psutil-7.2.2-cp37-abi3-win_arm64.whl", hash = "sha256:8c233660f575a5a89e6d4cb65d9f938126312bca76d8fe087b947b3a1aaac9ee", size = 134617, upload-time = "2026-01-28T18:15:36.514Z" },
]

[[package]]
name = "ptyprocess"
version = "0.7.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/20/e5/16ff212c1e452235a90aeb09066144d0c5a6a8c0834397e03f5224495c4e/ptyprocess-0.7.0.tar.gz", hash = "sha256:5c5d0a3b48ceee0b48485e0c26037c0acd7d29765ca3fbb5cb3831d347423220", size = 70762, upload-time = "2020-12-28T15:15:30.155Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/22/a6/858897256d0deac81a172289110f31629fc4cee19b6f01283303e18c8db3/ptyprocess-0.7.0-py2.py3-none-any.whl", hash = "sha256:4b41f3967fce3af57cc7e94b888626c18bf37a083e3651ca8feeb66d492fef35", size = 13993, upload-time = "2020-12-28T15:15:28.35Z" },
]

[[package]]
name = "pure-eval"
version = "0.2.3"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/cd/05/0a34433a064256a578f1783a10da6df098ceaa4a57bbeaa96a6c0352786b/pure_eval-0.2.3.tar.gz", hash = "sha256:5f4e983f40564c576c7c8635ae88db5956bb2229d7e9237d03b3c0b0190eaf42", size = 19752, upload-time = "2024-07-21T12:58:21.801Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/8e/37/efad0257dc6e593a18957422533ff0f87ede7c9c6ea010a2177d738fb82f/pure_eval-0.2.3-py3-none-any.whl", hash = "sha256:1db8e35b67b3d218d818ae653e27f06c3aa420901fa7b081ca98cbedc874e0d0", size = 11842, upload-time = "2024-07-21T12:58:20.04Z" },
]

[[package]]
name = "pycparser"
version = "3.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/1b/7d/92392ff7815c21062bea51aa7b87d45576f649f16458d78b7cf94b9ab2e6/pycparser-3.0.tar.gz", hash = "sha256:600f49d217304a5902ac3c37e1281c9fe94e4d0489de643a9504c5cdfdfc6b29", size = 103492, upload-time = "2026-01-21T14:26:51.89Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/0c/c3/44f3fbbfa403ea2a7c779186dc20772604442dde72947e7d01069cbe98e3/pycparser-3.0-py3-none-any.whl", hash = "sha256:b727414169a36b7d524c1c3e31839a521725078d7b2ff038656844266160a992", size = 48172, upload-time = "2026-01-21T14:26:50.693Z" },
]

[[package]]
name = "pygments"
version = "2.20.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/c3/b2/bc9c9196916376152d655522fdcebac55e66de6603a76a02bca1b6414f6c/pygments-2.20.0.tar.gz", hash = "sha256:6757cd03768053ff99f3039c1a36d6c0aa0b263438fcab17520b30a303a82b5f", size = 4955991, upload-time = "2026-03-29T13:29:33.898Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/f4/7e/a72dd26f3b0f4f2bf1dd8923c85f7ceb43172af56d63c7383eb62b332364/pygments-2.20.0-py3-none-any.whl", hash = "sha256:81a9e26dd42fd28a23a2d169d86d7ac03b46e2f8b59ed4698fb4785f946d0176", size = 1231151, upload-time = "2026-03-29T13:29:30.038Z" },
]

[[package]]
name = "python-dateutil"
version = "2.9.0.post0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "six" },
]
sdist = { url = "https://files.pythonhosted.org/packages/66/c0/0c8b6ad9f17a802ee498c46e004a0eb49bc148f2fd230864601a86dcf6db/python-dateutil-2.9.0.post0.tar.gz", hash = "sha256:37dd54208da7e1cd875388217d5e00ebd4179249f90fb72437e91a35459a0ad3", size = 342432, upload-time = "2024-03-01T18:36:20.211Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/ec/57/56b9bcc3c9c6a792fcbaf139543cee77261f3651ca9da0c93f5c1221264b/python_dateutil-2.9.0.post0-py2.py3-none-any.whl", hash = "sha256:a8b2bc7bffae282281c8140a97d3aa9c14da0b136dfe83f850eea9a5f7470427", size = 229892, upload-time = "2024-03-01T18:36:18.57Z" },
]

[[package]]
name = "pyzmq"
version = "27.1.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "cffi", marker = "implementation_name == 'pypy'" },
]
sdist = { url = "https://files.pythonhosted.org/packages/04/0b/3c9baedbdf613ecaa7aa07027780b8867f57b6293b6ee50de316c9f3222b/pyzmq-27.1.0.tar.gz", hash = "sha256:ac0765e3d44455adb6ddbf4417dcce460fc40a05978c08efdf2948072f6db540", size = 281750, upload-time = "2025-09-08T23:10:18.157Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/92/e7/038aab64a946d535901103da16b953c8c9cc9c961dadcbf3609ed6428d23/pyzmq-27.1.0-cp312-abi3-macosx_10_15_universal2.whl", hash = "sha256:452631b640340c928fa343801b0d07eb0c3789a5ffa843f6e1a9cee0ba4eb4fc", size = 1306279, upload-time = "2025-09-08T23:08:03.807Z" },
    { url = "https://files.pythonhosted.org/packages/e8/5e/c3c49fdd0f535ef45eefcc16934648e9e59dace4a37ee88fc53f6cd8e641/pyzmq-27.1.0-cp312-abi3-manylinux2014_i686.manylinux_2_17_i686.whl", hash = "sha256:1c179799b118e554b66da67d88ed66cd37a169f1f23b5d9f0a231b4e8d44a113", size = 895645, upload-time = "2025-09-08T23:08:05.301Z" },
    { url = "https://files.pythonhosted.org/packages/f8/e5/b0b2504cb4e903a74dcf1ebae157f9e20ebb6ea76095f6cfffea28c42ecd/pyzmq-27.1.0-cp312-abi3-manylinux_2_26_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:3837439b7f99e60312f0c926a6ad437b067356dc2bc2ec96eb395fd0fe804233", size = 652574, upload-time = "2025-09-08T23:08:06.828Z" },
    { url = "https://files.pythonhosted.org/packages/f8/9b/c108cdb55560eaf253f0cbdb61b29971e9fb34d9c3499b0e96e4e60ed8a5/pyzmq-27.1.0-cp312-abi3-manylinux_2_26_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:43ad9a73e3da1fab5b0e7e13402f0b2fb934ae1c876c51d0afff0e7c052eca31", size = 840995, upload-time = "2025-09-08T23:08:08.396Z" },
    { url = "https://files.pythonhosted.org/packages/c2/bb/b79798ca177b9eb0825b4c9998c6af8cd2a7f15a6a1a4272c1d1a21d382f/pyzmq-27.1.0-cp312-abi3-musllinux_1_2_aarch64.whl", hash = "sha256:0de3028d69d4cdc475bfe47a6128eb38d8bc0e8f4d69646adfbcd840facbac28", size = 1642070, upload-time = "2025-09-08T23:08:09.989Z" },
    { url = "https://files.pythonhosted.org/packages/9c/80/2df2e7977c4ede24c79ae39dcef3899bfc5f34d1ca7a5b24f182c9b7a9ca/pyzmq-27.1.0-cp312-abi3-musllinux_1_2_i686.whl", hash = "sha256:cf44a7763aea9298c0aa7dbf859f87ed7012de8bda0f3977b6fb1d96745df856", size = 2021121, upload-time = "2025-09-08T23:08:11.907Z" },
    { url = "https://files.pythonhosted.org/packages/46/bd/2d45ad24f5f5ae7e8d01525eb76786fa7557136555cac7d929880519e33a/pyzmq-27.1.0-cp312-abi3-musllinux_1_2_x86_64.whl", hash = "sha256:f30f395a9e6fbca195400ce833c731e7b64c3919aa481af4d88c3759e0cb7496", size = 1878550, upload-time = "2025-09-08T23:08:13.513Z" },
    { url = "https://files.pythonhosted.org/packages/e6/2f/104c0a3c778d7c2ab8190e9db4f62f0b6957b53c9d87db77c284b69f33ea/pyzmq-27.1.0-cp312-abi3-win32.whl", hash = "sha256:250e5436a4ba13885494412b3da5d518cd0d3a278a1ae640e113c073a5f88edd", size = 559184, upload-time = "2025-09-08T23:08:15.163Z" },
    { url = "https://files.pythonhosted.org/packages/fc/7f/a21b20d577e4100c6a41795842028235998a643b1ad406a6d4163ea8f53e/pyzmq-27.1.0-cp312-abi3-win_amd64.whl", hash = "sha256:9ce490cf1d2ca2ad84733aa1d69ce6855372cb5ce9223802450c9b2a7cba0ccf", size = 619480, upload-time = "2025-09-08T23:08:17.192Z" },
    { url = "https://files.pythonhosted.org/packages/78/c2/c012beae5f76b72f007a9e91ee9401cb88c51d0f83c6257a03e785c81cc2/pyzmq-27.1.0-cp312-abi3-win_arm64.whl", hash = "sha256:75a2f36223f0d535a0c919e23615fc85a1e23b71f40c7eb43d7b1dedb4d8f15f", size = 552993, upload-time = "2025-09-08T23:08:18.926Z" },
    { url = "https://files.pythonhosted.org/packages/60/cb/84a13459c51da6cec1b7b1dc1a47e6db6da50b77ad7fd9c145842750a011/pyzmq-27.1.0-cp313-cp313-android_24_arm64_v8a.whl", hash = "sha256:93ad4b0855a664229559e45c8d23797ceac03183c7b6f5b4428152a6b06684a5", size = 1122436, upload-time = "2025-09-08T23:08:20.801Z" },
    { url = "https://files.pythonhosted.org/packages/dc/b6/94414759a69a26c3dd674570a81813c46a078767d931a6c70ad29fc585cb/pyzmq-27.1.0-cp313-cp313-android_24_x86_64.whl", hash = "sha256:fbb4f2400bfda24f12f009cba62ad5734148569ff4949b1b6ec3b519444342e6", size = 1156301, upload-time = "2025-09-08T23:08:22.47Z" },
    { url = "https://files.pythonhosted.org/packages/a5/ad/15906493fd40c316377fd8a8f6b1f93104f97a752667763c9b9c1b71d42d/pyzmq-27.1.0-cp313-cp313t-macosx_10_15_universal2.whl", hash = "sha256:e343d067f7b151cfe4eb3bb796a7752c9d369eed007b91231e817071d2c2fec7", size = 1341197, upload-time = "2025-09-08T23:08:24.286Z" },
    { url = "https://files.pythonhosted.org/packages/14/1d/d343f3ce13db53a54cb8946594e567410b2125394dafcc0268d8dda027e0/pyzmq-27.1.0-cp313-cp313t-manylinux2014_i686.manylinux_2_17_i686.whl", hash = "sha256:08363b2011dec81c354d694bdecaef4770e0ae96b9afea70b3f47b973655cc05", size = 897275, upload-time = "2025-09-08T23:08:26.063Z" },
    { url = "https://files.pythonhosted.org/packages/69/2d/d83dd6d7ca929a2fc67d2c3005415cdf322af7751d773524809f9e585129/pyzmq-27.1.0-cp313-cp313t-manylinux_2_26_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:d54530c8c8b5b8ddb3318f481297441af102517602b569146185fa10b63f4fa9", size = 660469, upload-time = "2025-09-08T23:08:27.623Z" },
    { url = "https://files.pythonhosted.org/packages/3e/cd/9822a7af117f4bc0f1952dbe9ef8358eb50a24928efd5edf54210b850259/pyzmq-27.1.0-cp313-cp313t-manylinux_2_26_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:6f3afa12c392f0a44a2414056d730eebc33ec0926aae92b5ad5cf26ebb6cc128", size = 847961, upload-time = "2025-09-08T23:08:29.672Z" },
    { url = "https://files.pythonhosted.org/packages/9a/12/f003e824a19ed73be15542f172fd0ec4ad0b60cf37436652c93b9df7c585/pyzmq-27.1.0-cp313-cp313t-musllinux_1_2_aarch64.whl", hash = "sha256:c65047adafe573ff023b3187bb93faa583151627bc9c51fc4fb2c561ed689d39", size = 1650282, upload-time = "2025-09-08T23:08:31.349Z" },
    { url = "https://files.pythonhosted.org/packages/d5/4a/e82d788ed58e9a23995cee70dbc20c9aded3d13a92d30d57ec2291f1e8a3/pyzmq-27.1.0-cp313-cp313t-musllinux_1_2_i686.whl", hash = "sha256:90e6e9441c946a8b0a667356f7078d96411391a3b8f80980315455574177ec97", size = 2024468, upload-time = "2025-09-08T23:08:33.543Z" },
    { url = "https://files.pythonhosted.org/packages/d9/94/2da0a60841f757481e402b34bf4c8bf57fa54a5466b965de791b1e6f747d/pyzmq-27.1.0-cp313-cp313t-musllinux_1_2_x86_64.whl", hash = "sha256:add071b2d25f84e8189aaf0882d39a285b42fa3853016ebab234a5e78c7a43db", size = 1885394, upload-time = "2025-09-08T23:08:35.51Z" },
    { url = "https://files.pythonhosted.org/packages/4f/6f/55c10e2e49ad52d080dc24e37adb215e5b0d64990b57598abc2e3f01725b/pyzmq-27.1.0-cp313-cp313t-win32.whl", hash = "sha256:7ccc0700cfdf7bd487bea8d850ec38f204478681ea02a582a8da8171b7f90a1c", size = 574964, upload-time = "2025-09-08T23:08:37.178Z" },
    { url = "https://files.pythonhosted.org/packages/87/4d/2534970ba63dd7c522d8ca80fb92777f362c0f321900667c615e2067cb29/pyzmq-27.1.0-cp313-cp313t-win_amd64.whl", hash = "sha256:8085a9fba668216b9b4323be338ee5437a235fe275b9d1610e422ccc279733e2", size = 641029, upload-time = "2025-09-08T23:08:40.595Z" },
    { url = "https://files.pythonhosted.org/packages/f6/fa/f8aea7a28b0641f31d40dea42d7ef003fded31e184ef47db696bc74cd610/pyzmq-27.1.0-cp313-cp313t-win_arm64.whl", hash = "sha256:6bb54ca21bcfe361e445256c15eedf083f153811c37be87e0514934d6913061e", size = 561541, upload-time = "2025-09-08T23:08:42.668Z" },
    { url = "https://files.pythonhosted.org/packages/87/45/19efbb3000956e82d0331bafca5d9ac19ea2857722fa2caacefb6042f39d/pyzmq-27.1.0-cp314-cp314t-macosx_10_15_universal2.whl", hash = "sha256:ce980af330231615756acd5154f29813d553ea555485ae712c491cd483df6b7a", size = 1341197, upload-time = "2025-09-08T23:08:44.973Z" },
    { url = "https://files.pythonhosted.org/packages/48/43/d72ccdbf0d73d1343936296665826350cb1e825f92f2db9db3e61c2162a2/pyzmq-27.1.0-cp314-cp314t-manylinux2014_i686.manylinux_2_17_i686.whl", hash = "sha256:1779be8c549e54a1c38f805e56d2a2e5c009d26de10921d7d51cfd1c8d4632ea", size = 897175, upload-time = "2025-09-08T23:08:46.601Z" },
    { url = "https://files.pythonhosted.org/packages/2f/2e/a483f73a10b65a9ef0161e817321d39a770b2acf8bcf3004a28d90d14a94/pyzmq-27.1.0-cp314-cp314t-manylinux_2_26_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:7200bb0f03345515df50d99d3db206a0a6bee1955fbb8c453c76f5bf0e08fb96", size = 660427, upload-time = "2025-09-08T23:08:48.187Z" },
    { url = "https://files.pythonhosted.org/packages/f5/d2/5f36552c2d3e5685abe60dfa56f91169f7a2d99bbaf67c5271022ab40863/pyzmq-27.1.0-cp314-cp314t-manylinux_2_26_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:01c0e07d558b06a60773744ea6251f769cd79a41a97d11b8bf4ab8f034b0424d", size = 847929, upload-time = "2025-09-08T23:08:49.76Z" },
    { url = "https://files.pythonhosted.org/packages/c4/2a/404b331f2b7bf3198e9945f75c4c521f0c6a3a23b51f7a4a401b94a13833/pyzmq-27.1.0-cp314-cp314t-musllinux_1_2_aarch64.whl", hash = "sha256:80d834abee71f65253c91540445d37c4c561e293ba6e741b992f20a105d69146", size = 1650193, upload-time = "2025-09-08T23:08:51.7Z" },
    { url = "https://files.pythonhosted.org/packages/1c/0b/f4107e33f62a5acf60e3ded67ed33d79b4ce18de432625ce2fc5093d6388/pyzmq-27.1.0-cp314-cp314t-musllinux_1_2_i686.whl", hash = "sha256:544b4e3b7198dde4a62b8ff6685e9802a9a1ebf47e77478a5eb88eca2a82f2fd", size = 2024388, upload-time = "2025-09-08T23:08:53.393Z" },
    { url = "https://files.pythonhosted.org/packages/0d/01/add31fe76512642fd6e40e3a3bd21f4b47e242c8ba33efb6809e37076d9b/pyzmq-27.1.0-cp314-cp314t-musllinux_1_2_x86_64.whl", hash = "sha256:cedc4c68178e59a4046f97eca31b148ddcf51e88677de1ef4e78cf06c5376c9a", size = 1885316, upload-time = "2025-09-08T23:08:55.702Z" },
    { url = "https://files.pythonhosted.org/packages/c4/59/a5f38970f9bf07cee96128de79590bb354917914a9be11272cfc7ff26af0/pyzmq-27.1.0-cp314-cp314t-win32.whl", hash = "sha256:1f0b2a577fd770aa6f053211a55d1c47901f4d537389a034c690291485e5fe92", size = 587472, upload-time = "2025-09-08T23:08:58.18Z" },
    { url = "https://files.pythonhosted.org/packages/70/d8/78b1bad170f93fcf5e3536e70e8fadac55030002275c9a29e8f5719185de/pyzmq-27.1.0-cp314-cp314t-win_amd64.whl", hash = "sha256:19c9468ae0437f8074af379e986c5d3d7d7bfe033506af442e8c879732bedbe0", size = 661401, upload-time = "2025-09-08T23:08:59.802Z" },
    { url = "https://files.pythonhosted.org/packages/81/d6/4bfbb40c9a0b42fc53c7cf442f6385db70b40f74a783130c5d0a5aa62228/pyzmq-27.1.0-cp314-cp314t-win_arm64.whl", hash = "sha256:dc5dbf68a7857b59473f7df42650c621d7e8923fb03fa74a526890f4d33cc4d7", size = 575170, upload-time = "2025-09-08T23:09:01.418Z" },
]

[[package]]
name = "scikit-learn"
version = "1.8.0"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "joblib" },
    { name = "numpy" },
    { name = "scipy" },
    { name = "threadpoolctl" },
]
sdist = { url = "https://files.pythonhosted.org/packages/0e/d4/40988bf3b8e34feec1d0e6a051446b1f66225f8529b9309becaeef62b6c4/scikit_learn-1.8.0.tar.gz", hash = "sha256:9bccbb3b40e3de10351f8f5068e105d0f4083b1a65fa07b6634fbc401a6287fd", size = 7335585, upload-time = "2025-12-10T07:08:53.618Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/90/74/e6a7cc4b820e95cc38cf36cd74d5aa2b42e8ffc2d21fe5a9a9c45c1c7630/scikit_learn-1.8.0-cp312-cp312-macosx_10_13_x86_64.whl", hash = "sha256:5fb63362b5a7ddab88e52b6dbb47dac3fd7dafeee740dc6c8d8a446ddedade8e", size = 8548242, upload-time = "2025-12-10T07:07:51.568Z" },
    { url = "https://files.pythonhosted.org/packages/49/d8/9be608c6024d021041c7f0b3928d4749a706f4e2c3832bbede4fb4f58c95/scikit_learn-1.8.0-cp312-cp312-macosx_12_0_arm64.whl", hash = "sha256:5025ce924beccb28298246e589c691fe1b8c1c96507e6d27d12c5fadd85bfd76", size = 8079075, upload-time = "2025-12-10T07:07:53.697Z" },
    { url = "https://files.pythonhosted.org/packages/dd/47/f187b4636ff80cc63f21cd40b7b2d177134acaa10f6bb73746130ee8c2e5/scikit_learn-1.8.0-cp312-cp312-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:4496bb2cf7a43ce1a2d7524a79e40bc5da45cf598dbf9545b7e8316ccba47bb4", size = 8660492, upload-time = "2025-12-10T07:07:55.574Z" },
    { url = "https://files.pythonhosted.org/packages/97/74/b7a304feb2b49df9fafa9382d4d09061a96ee9a9449a7cbea7988dda0828/scikit_learn-1.8.0-cp312-cp312-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:a0bcfe4d0d14aec44921545fd2af2338c7471de9cb701f1da4c9d85906ab847a", size = 8931904, upload-time = "2025-12-10T07:07:57.666Z" },
    { url = "https://files.pythonhosted.org/packages/9f/c4/0ab22726a04ede56f689476b760f98f8f46607caecff993017ac1b64aa5d/scikit_learn-1.8.0-cp312-cp312-win_amd64.whl", hash = "sha256:35c007dedb2ffe38fe3ee7d201ebac4a2deccd2408e8621d53067733e3c74809", size = 8019359, upload-time = "2025-12-10T07:07:59.838Z" },
    { url = "https://files.pythonhosted.org/packages/24/90/344a67811cfd561d7335c1b96ca21455e7e472d281c3c279c4d3f2300236/scikit_learn-1.8.0-cp312-cp312-win_arm64.whl", hash = "sha256:8c497fff237d7b4e07e9ef1a640887fa4fb765647f86fbe00f969ff6280ce2bb", size = 7641898, upload-time = "2025-12-10T07:08:01.36Z" },
    { url = "https://files.pythonhosted.org/packages/03/aa/e22e0768512ce9255eba34775be2e85c2048da73da1193e841707f8f039c/scikit_learn-1.8.0-cp313-cp313-macosx_10_13_x86_64.whl", hash = "sha256:0d6ae97234d5d7079dc0040990a6f7aeb97cb7fa7e8945f1999a429b23569e0a", size = 8513770, upload-time = "2025-12-10T07:08:03.251Z" },
    { url = "https://files.pythonhosted.org/packages/58/37/31b83b2594105f61a381fc74ca19e8780ee923be2d496fcd8d2e1147bd99/scikit_learn-1.8.0-cp313-cp313-macosx_12_0_arm64.whl", hash = "sha256:edec98c5e7c128328124a029bceb09eda2d526997780fef8d65e9a69eead963e", size = 8044458, upload-time = "2025-12-10T07:08:05.336Z" },
    { url = "https://files.pythonhosted.org/packages/2d/5a/3f1caed8765f33eabb723596666da4ebbf43d11e96550fb18bdec42b467b/scikit_learn-1.8.0-cp313-cp313-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:74b66d8689d52ed04c271e1329f0c61635bcaf5b926db9b12d58914cdc01fe57", size = 8610341, upload-time = "2025-12-10T07:08:07.732Z" },
    { url = "https://files.pythonhosted.org/packages/38/cf/06896db3f71c75902a8e9943b444a56e727418f6b4b4a90c98c934f51ed4/scikit_learn-1.8.0-cp313-cp313-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:8fdf95767f989b0cfedb85f7ed8ca215d4be728031f56ff5a519ee1e3276dc2e", size = 8900022, upload-time = "2025-12-10T07:08:09.862Z" },
    { url = "https://files.pythonhosted.org/packages/1c/f9/9b7563caf3ec8873e17a31401858efab6b39a882daf6c1bfa88879c0aa11/scikit_learn-1.8.0-cp313-cp313-win_amd64.whl", hash = "sha256:2de443b9373b3b615aec1bb57f9baa6bb3a9bd093f1269ba95c17d870422b271", size = 7989409, upload-time = "2025-12-10T07:08:12.028Z" },
    { url = "https://files.pythonhosted.org/packages/49/bd/1f4001503650e72c4f6009ac0c4413cb17d2d601cef6f71c0453da2732fc/scikit_learn-1.8.0-cp313-cp313-win_arm64.whl", hash = "sha256:eddde82a035681427cbedded4e6eff5e57fa59216c2e3e90b10b19ab1d0a65c3", size = 7619760, upload-time = "2025-12-10T07:08:13.688Z" },
    { url = "https://files.pythonhosted.org/packages/d2/7d/a630359fc9dcc95496588c8d8e3245cc8fd81980251079bc09c70d41d951/scikit_learn-1.8.0-cp313-cp313t-macosx_10_13_x86_64.whl", hash = "sha256:7cc267b6108f0a1499a734167282c00c4ebf61328566b55ef262d48e9849c735", size = 8826045, upload-time = "2025-12-10T07:08:15.215Z" },
    { url = "https://files.pythonhosted.org/packages/cc/56/a0c86f6930cfcd1c7054a2bc417e26960bb88d32444fe7f71d5c2cfae891/scikit_learn-1.8.0-cp313-cp313t-macosx_12_0_arm64.whl", hash = "sha256:fe1c011a640a9f0791146011dfd3c7d9669785f9fed2b2a5f9e207536cf5c2fd", size = 8420324, upload-time = "2025-12-10T07:08:17.561Z" },
    { url = "https://files.pythonhosted.org/packages/46/1e/05962ea1cebc1cf3876667ecb14c283ef755bf409993c5946ade3b77e303/scikit_learn-1.8.0-cp313-cp313t-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:72358cce49465d140cc4e7792015bb1f0296a9742d5622c67e31399b75468b9e", size = 8680651, upload-time = "2025-12-10T07:08:19.952Z" },
    { url = "https://files.pythonhosted.org/packages/fe/56/a85473cd75f200c9759e3a5f0bcab2d116c92a8a02ee08ccd73b870f8bb4/scikit_learn-1.8.0-cp313-cp313t-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:80832434a6cc114f5219211eec13dcbc16c2bac0e31ef64c6d346cde3cf054cb", size = 8925045, upload-time = "2025-12-10T07:08:22.11Z" },
    { url = "https://files.pythonhosted.org/packages/cc/b7/64d8cfa896c64435ae57f4917a548d7ac7a44762ff9802f75a79b77cb633/scikit_learn-1.8.0-cp313-cp313t-win_amd64.whl", hash = "sha256:ee787491dbfe082d9c3013f01f5991658b0f38aa8177e4cd4bf434c58f551702", size = 8507994, upload-time = "2025-12-10T07:08:23.943Z" },
    { url = "https://files.pythonhosted.org/packages/5e/37/e192ea709551799379958b4c4771ec507347027bb7c942662c7fbeba31cb/scikit_learn-1.8.0-cp313-cp313t-win_arm64.whl", hash = "sha256:bf97c10a3f5a7543f9b88cbf488d33d175e9146115a451ae34568597ba33dcde", size = 7869518, upload-time = "2025-12-10T07:08:25.71Z" },
    { url = "https://files.pythonhosted.org/packages/24/05/1af2c186174cc92dcab2233f327336058c077d38f6fe2aceb08e6ab4d509/scikit_learn-1.8.0-cp314-cp314-macosx_10_15_x86_64.whl", hash = "sha256:c22a2da7a198c28dd1a6e1136f19c830beab7fdca5b3e5c8bba8394f8a5c45b3", size = 8528667, upload-time = "2025-12-10T07:08:27.541Z" },
    { url = "https://files.pythonhosted.org/packages/a8/25/01c0af38fe969473fb292bba9dc2b8f9b451f3112ff242c647fee3d0dfe7/scikit_learn-1.8.0-cp314-cp314-macosx_12_0_arm64.whl", hash = "sha256:6b595b07a03069a2b1740dc08c2299993850ea81cce4fe19b2421e0c970de6b7", size = 8066524, upload-time = "2025-12-10T07:08:29.822Z" },
    { url = "https://files.pythonhosted.org/packages/be/ce/a0623350aa0b68647333940ee46fe45086c6060ec604874e38e9ab7d8e6c/scikit_learn-1.8.0-cp314-cp314-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:29ffc74089f3d5e87dfca4c2c8450f88bdc61b0fc6ed5d267f3988f19a1309f6", size = 8657133, upload-time = "2025-12-10T07:08:31.865Z" },
    { url = "https://files.pythonhosted.org/packages/b8/cb/861b41341d6f1245e6ca80b1c1a8c4dfce43255b03df034429089ca2a2c5/scikit_learn-1.8.0-cp314-cp314-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:fb65db5d7531bccf3a4f6bec3462223bea71384e2cda41da0f10b7c292b9e7c4", size = 8923223, upload-time = "2025-12-10T07:08:34.166Z" },
    { url = "https://files.pythonhosted.org/packages/76/18/a8def8f91b18cd1ba6e05dbe02540168cb24d47e8dcf69e8d00b7da42a08/scikit_learn-1.8.0-cp314-cp314-win_amd64.whl", hash = "sha256:56079a99c20d230e873ea40753102102734c5953366972a71d5cb39a32bc40c6", size = 8096518, upload-time = "2025-12-10T07:08:36.339Z" },
    { url = "https://files.pythonhosted.org/packages/d1/77/482076a678458307f0deb44e29891d6022617b2a64c840c725495bee343f/scikit_learn-1.8.0-cp314-cp314-win_arm64.whl", hash = "sha256:3bad7565bc9cf37ce19a7c0d107742b320c1285df7aab1a6e2d28780df167242", size = 7754546, upload-time = "2025-12-10T07:08:38.128Z" },
    { url = "https://files.pythonhosted.org/packages/2d/d1/ef294ca754826daa043b2a104e59960abfab4cf653891037d19dd5b6f3cf/scikit_learn-1.8.0-cp314-cp314t-macosx_10_15_x86_64.whl", hash = "sha256:4511be56637e46c25721e83d1a9cea9614e7badc7040c4d573d75fbe257d6fd7", size = 8848305, upload-time = "2025-12-10T07:08:41.013Z" },
    { url = "https://files.pythonhosted.org/packages/5b/e2/b1f8b05138ee813b8e1a4149f2f0d289547e60851fd1bb268886915adbda/scikit_learn-1.8.0-cp314-cp314t-macosx_12_0_arm64.whl", hash = "sha256:a69525355a641bf8ef136a7fa447672fb54fe8d60cab5538d9eb7c6438543fb9", size = 8432257, upload-time = "2025-12-10T07:08:42.873Z" },
    { url = "https://files.pythonhosted.org/packages/26/11/c32b2138a85dcb0c99f6afd13a70a951bfdff8a6ab42d8160522542fb647/scikit_learn-1.8.0-cp314-cp314t-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:c2656924ec73e5939c76ac4c8b026fc203b83d8900362eb2599d8aee80e4880f", size = 8678673, upload-time = "2025-12-10T07:08:45.362Z" },
    { url = "https://files.pythonhosted.org/packages/c7/57/51f2384575bdec454f4fe4e7a919d696c9ebce914590abf3e52d47607ab8/scikit_learn-1.8.0-cp314-cp314t-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:15fc3b5d19cc2be65404786857f2e13c70c83dd4782676dd6814e3b89dc8f5b9", size = 8922467, upload-time = "2025-12-10T07:08:47.408Z" },
    { url = "https://files.pythonhosted.org/packages/35/4d/748c9e2872637a57981a04adc038dacaa16ba8ca887b23e34953f0b3f742/scikit_learn-1.8.0-cp314-cp314t-win_amd64.whl", hash = "sha256:00d6f1d66fbcf4eba6e356e1420d33cc06c70a45bb1363cd6f6a8e4ebbbdece2", size = 8774395, upload-time = "2025-12-10T07:08:49.337Z" },
    { url = "https://files.pythonhosted.org/packages/60/22/d7b2ebe4704a5e50790ba089d5c2ae308ab6bb852719e6c3bd4f04c3a363/scikit_learn-1.8.0-cp314-cp314t-win_arm64.whl", hash = "sha256:f28dd15c6bb0b66ba09728cf09fd8736c304be29409bd8445a080c1280619e8c", size = 8002647, upload-time = "2025-12-10T07:08:51.601Z" },
]

[[package]]
name = "scipy"
version = "1.17.1"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "numpy" },
]
sdist = { url = "https://files.pythonhosted.org/packages/7a/97/5a3609c4f8d58b039179648e62dd220f89864f56f7357f5d4f45c29eb2cc/scipy-1.17.1.tar.gz", hash = "sha256:95d8e012d8cb8816c226aef832200b1d45109ed4464303e997c5b13122b297c0", size = 30573822, upload-time = "2026-02-23T00:26:24.851Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/35/48/b992b488d6f299dbe3f11a20b24d3dda3d46f1a635ede1c46b5b17a7b163/scipy-1.17.1-cp312-cp312-macosx_10_14_x86_64.whl", hash = "sha256:35c3a56d2ef83efc372eaec584314bd0ef2e2f0d2adb21c55e6ad5b344c0dcb8", size = 31610954, upload-time = "2026-02-23T00:17:49.855Z" },
    { url = "https://files.pythonhosted.org/packages/b2/02/cf107b01494c19dc100f1d0b7ac3cc08666e96ba2d64db7626066cee895e/scipy-1.17.1-cp312-cp312-macosx_12_0_arm64.whl", hash = "sha256:fcb310ddb270a06114bb64bbe53c94926b943f5b7f0842194d585c65eb4edd76", size = 28172662, upload-time = "2026-02-23T00:18:01.64Z" },
    { url = "https://files.pythonhosted.org/packages/cf/a9/599c28631bad314d219cf9ffd40e985b24d603fc8a2f4ccc5ae8419a535b/scipy-1.17.1-cp312-cp312-macosx_14_0_arm64.whl", hash = "sha256:cc90d2e9c7e5c7f1a482c9875007c095c3194b1cfedca3c2f3291cdc2bc7c086", size = 20344366, upload-time = "2026-02-23T00:18:12.015Z" },
    { url = "https://files.pythonhosted.org/packages/35/f5/906eda513271c8deb5af284e5ef0206d17a96239af79f9fa0aebfe0e36b4/scipy-1.17.1-cp312-cp312-macosx_14_0_x86_64.whl", hash = "sha256:c80be5ede8f3f8eded4eff73cc99a25c388ce98e555b17d31da05287015ffa5b", size = 22704017, upload-time = "2026-02-23T00:18:21.502Z" },
    { url = "https://files.pythonhosted.org/packages/da/34/16f10e3042d2f1d6b66e0428308ab52224b6a23049cb2f5c1756f713815f/scipy-1.17.1-cp312-cp312-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:e19ebea31758fac5893a2ac360fedd00116cbb7628e650842a6691ba7ca28a21", size = 32927842, upload-time = "2026-02-23T00:18:35.367Z" },
    { url = "https://files.pythonhosted.org/packages/01/8e/1e35281b8ab6d5d72ebe9911edcdffa3f36b04ed9d51dec6dd140396e220/scipy-1.17.1-cp312-cp312-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:02ae3b274fde71c5e92ac4d54bc06c42d80e399fec704383dcd99b301df37458", size = 35235890, upload-time = "2026-02-23T00:18:49.188Z" },
    { url = "https://files.pythonhosted.org/packages/c5/5c/9d7f4c88bea6e0d5a4f1bc0506a53a00e9fcb198de372bfe4d3652cef482/scipy-1.17.1-cp312-cp312-musllinux_1_2_aarch64.whl", hash = "sha256:8a604bae87c6195d8b1045eddece0514d041604b14f2727bbc2b3020172045eb", size = 35003557, upload-time = "2026-02-23T00:18:54.74Z" },
    { url = "https://files.pythonhosted.org/packages/65/94/7698add8f276dbab7a9de9fb6b0e02fc13ee61d51c7c3f85ac28b65e1239/scipy-1.17.1-cp312-cp312-musllinux_1_2_x86_64.whl", hash = "sha256:f590cd684941912d10becc07325a3eeb77886fe981415660d9265c4c418d0bea", size = 37625856, upload-time = "2026-02-23T00:19:00.307Z" },
    { url = "https://files.pythonhosted.org/packages/a2/84/dc08d77fbf3d87d3ee27f6a0c6dcce1de5829a64f2eae85a0ecc1f0daa73/scipy-1.17.1-cp312-cp312-win_amd64.whl", hash = "sha256:41b71f4a3a4cab9d366cd9065b288efc4d4f3c0b37a91a8e0947fb5bd7f31d87", size = 36549682, upload-time = "2026-02-23T00:19:07.67Z" },
    { url = "https://files.pythonhosted.org/packages/bc/98/fe9ae9ffb3b54b62559f52dedaebe204b408db8109a8c66fdd04869e6424/scipy-1.17.1-cp312-cp312-win_arm64.whl", hash = "sha256:f4115102802df98b2b0db3cce5cb9b92572633a1197c77b7553e5203f284a5b3", size = 24547340, upload-time = "2026-02-23T00:19:12.024Z" },
    { url = "https://files.pythonhosted.org/packages/76/27/07ee1b57b65e92645f219b37148a7e7928b82e2b5dbeccecb4dff7c64f0b/scipy-1.17.1-cp313-cp313-macosx_10_14_x86_64.whl", hash = "sha256:5e3c5c011904115f88a39308379c17f91546f77c1667cea98739fe0fccea804c", size = 31590199, upload-time = "2026-02-23T00:19:17.192Z" },
    { url = "https://files.pythonhosted.org/packages/ec/ae/db19f8ab842e9b724bf5dbb7db29302a91f1e55bc4d04b1025d6d605a2c5/scipy-1.17.1-cp313-cp313-macosx_12_0_arm64.whl", hash = "sha256:6fac755ca3d2c3edcb22f479fceaa241704111414831ddd3bc6056e18516892f", size = 28154001, upload-time = "2026-02-23T00:19:22.241Z" },
    { url = "https://files.pythonhosted.org/packages/5b/58/3ce96251560107b381cbd6e8413c483bbb1228a6b919fa8652b0d4090e7f/scipy-1.17.1-cp313-cp313-macosx_14_0_arm64.whl", hash = "sha256:7ff200bf9d24f2e4d5dc6ee8c3ac64d739d3a89e2326ba68aaf6c4a2b838fd7d", size = 20325719, upload-time = "2026-02-23T00:19:26.329Z" },
    { url = "https://files.pythonhosted.org/packages/b2/83/15087d945e0e4d48ce2377498abf5ad171ae013232ae31d06f336e64c999/scipy-1.17.1-cp313-cp313-macosx_14_0_x86_64.whl", hash = "sha256:4b400bdc6f79fa02a4d86640310dde87a21fba0c979efff5248908c6f15fad1b", size = 22683595, upload-time = "2026-02-23T00:19:30.304Z" },
    { url = "https://files.pythonhosted.org/packages/b4/e0/e58fbde4a1a594c8be8114eb4aac1a55bcd6587047efc18a61eb1f5c0d30/scipy-1.17.1-cp313-cp313-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:2b64ca7d4aee0102a97f3ba22124052b4bd2152522355073580bf4845e2550b6", size = 32896429, upload-time = "2026-02-23T00:19:35.536Z" },
    { url = "https://files.pythonhosted.org/packages/f5/5f/f17563f28ff03c7b6799c50d01d5d856a1d55f2676f537ca8d28c7f627cd/scipy-1.17.1-cp313-cp313-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:581b2264fc0aa555f3f435a5944da7504ea3a065d7029ad60e7c3d1ae09c5464", size = 35203952, upload-time = "2026-02-23T00:19:42.259Z" },
    { url = "https://files.pythonhosted.org/packages/8d/a5/9afd17de24f657fdfe4df9a3f1ea049b39aef7c06000c13db1530d81ccca/scipy-1.17.1-cp313-cp313-musllinux_1_2_aarch64.whl", hash = "sha256:beeda3d4ae615106d7094f7e7cef6218392e4465cc95d25f900bebabfded0950", size = 34979063, upload-time = "2026-02-23T00:19:47.547Z" },
    { url = "https://files.pythonhosted.org/packages/8b/13/88b1d2384b424bf7c924f2038c1c409f8d88bb2a8d49d097861dd64a57b2/scipy-1.17.1-cp313-cp313-musllinux_1_2_x86_64.whl", hash = "sha256:6609bc224e9568f65064cfa72edc0f24ee6655b47575954ec6339534b2798369", size = 37598449, upload-time = "2026-02-23T00:19:53.238Z" },
    { url = "https://files.pythonhosted.org/packages/35/e5/d6d0e51fc888f692a35134336866341c08655d92614f492c6860dc45bb2c/scipy-1.17.1-cp313-cp313-win_amd64.whl", hash = "sha256:37425bc9175607b0268f493d79a292c39f9d001a357bebb6b88fdfaff13f6448", size = 36510943, upload-time = "2026-02-23T00:20:50.89Z" },
    { url = "https://files.pythonhosted.org/packages/2a/fd/3be73c564e2a01e690e19cc618811540ba5354c67c8680dce3281123fb79/scipy-1.17.1-cp313-cp313-win_arm64.whl", hash = "sha256:5cf36e801231b6a2059bf354720274b7558746f3b1a4efb43fcf557ccd484a87", size = 24545621, upload-time = "2026-02-23T00:20:55.871Z" },
    { url = "https://files.pythonhosted.org/packages/6f/6b/17787db8b8114933a66f9dcc479a8272e4b4da75fe03b0c282f7b0ade8cd/scipy-1.17.1-cp313-cp313t-macosx_10_14_x86_64.whl", hash = "sha256:d59c30000a16d8edc7e64152e30220bfbd724c9bbb08368c054e24c651314f0a", size = 31936708, upload-time = "2026-02-23T00:19:58.694Z" },
    { url = "https://files.pythonhosted.org/packages/38/2e/524405c2b6392765ab1e2b722a41d5da33dc5c7b7278184a8ad29b6cb206/scipy-1.17.1-cp313-cp313t-macosx_12_0_arm64.whl", hash = "sha256:010f4333c96c9bb1a4516269e33cb5917b08ef2166d5556ca2fd9f082a9e6ea0", size = 28570135, upload-time = "2026-02-23T00:20:03.934Z" },
    { url = "https://files.pythonhosted.org/packages/fd/c3/5bd7199f4ea8556c0c8e39f04ccb014ac37d1468e6cfa6a95c6b3562b76e/scipy-1.17.1-cp313-cp313t-macosx_14_0_arm64.whl", hash = "sha256:2ceb2d3e01c5f1d83c4189737a42d9cb2fc38a6eeed225e7515eef71ad301dce", size = 20741977, upload-time = "2026-02-23T00:20:07.935Z" },
    { url = "https://files.pythonhosted.org/packages/d9/b8/8ccd9b766ad14c78386599708eb745f6b44f08400a5fd0ade7cf89b6fc93/scipy-1.17.1-cp313-cp313t-macosx_14_0_x86_64.whl", hash = "sha256:844e165636711ef41f80b4103ed234181646b98a53c8f05da12ca5ca289134f6", size = 23029601, upload-time = "2026-02-23T00:20:12.161Z" },
    { url = "https://files.pythonhosted.org/packages/6d/a0/3cb6f4d2fb3e17428ad2880333cac878909ad1a89f678527b5328b93c1d4/scipy-1.17.1-cp313-cp313t-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:158dd96d2207e21c966063e1635b1063cd7787b627b6f07305315dd73d9c679e", size = 33019667, upload-time = "2026-02-23T00:20:17.208Z" },
    { url = "https://files.pythonhosted.org/packages/f3/c3/2d834a5ac7bf3a0c806ad1508efc02dda3c8c61472a56132d7894c312dea/scipy-1.17.1-cp313-cp313t-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:74cbb80d93260fe2ffa334efa24cb8f2f0f622a9b9febf8b483c0b865bfb3475", size = 35264159, upload-time = "2026-02-23T00:20:23.087Z" },
    { url = "https://files.pythonhosted.org/packages/4d/77/d3ed4becfdbd217c52062fafe35a72388d1bd82c2d0ba5ca19d6fcc93e11/scipy-1.17.1-cp313-cp313t-musllinux_1_2_aarch64.whl", hash = "sha256:dbc12c9f3d185f5c737d801da555fb74b3dcfa1a50b66a1a93e09190f41fab50", size = 35102771, upload-time = "2026-02-23T00:20:28.636Z" },
    { url = "https://files.pythonhosted.org/packages/bd/12/d19da97efde68ca1ee5538bb261d5d2c062f0c055575128f11a2730e3ac1/scipy-1.17.1-cp313-cp313t-musllinux_1_2_x86_64.whl", hash = "sha256:94055a11dfebe37c656e70317e1996dc197e1a15bbcc351bcdd4610e128fe1ca", size = 37665910, upload-time = "2026-02-23T00:20:34.743Z" },
    { url = "https://files.pythonhosted.org/packages/06/1c/1172a88d507a4baaf72c5a09bb6c018fe2ae0ab622e5830b703a46cc9e44/scipy-1.17.1-cp313-cp313t-win_amd64.whl", hash = "sha256:e30bdeaa5deed6bc27b4cc490823cd0347d7dae09119b8803ae576ea0ce52e4c", size = 36562980, upload-time = "2026-02-23T00:20:40.575Z" },
    { url = "https://files.pythonhosted.org/packages/70/b0/eb757336e5a76dfa7911f63252e3b7d1de00935d7705cf772db5b45ec238/scipy-1.17.1-cp313-cp313t-win_arm64.whl", hash = "sha256:a720477885a9d2411f94a93d16f9d89bad0f28ca23c3f8daa521e2dcc3f44d49", size = 24856543, upload-time = "2026-02-23T00:20:45.313Z" },
    { url = "https://files.pythonhosted.org/packages/cf/83/333afb452af6f0fd70414dc04f898647ee1423979ce02efa75c3b0f2c28e/scipy-1.17.1-cp314-cp314-macosx_10_14_x86_64.whl", hash = "sha256:a48a72c77a310327f6a3a920092fa2b8fd03d7deaa60f093038f22d98e096717", size = 31584510, upload-time = "2026-02-23T00:21:01.015Z" },
    { url = "https://files.pythonhosted.org/packages/ed/a6/d05a85fd51daeb2e4ea71d102f15b34fedca8e931af02594193ae4fd25f7/scipy-1.17.1-cp314-cp314-macosx_12_0_arm64.whl", hash = "sha256:45abad819184f07240d8a696117a7aacd39787af9e0b719d00285549ed19a1e9", size = 28170131, upload-time = "2026-02-23T00:21:05.888Z" },
    { url = "https://files.pythonhosted.org/packages/db/7b/8624a203326675d7746a254083a187398090a179335b2e4a20e2ddc46e83/scipy-1.17.1-cp314-cp314-macosx_14_0_arm64.whl", hash = "sha256:3fd1fcdab3ea951b610dc4cef356d416d5802991e7e32b5254828d342f7b7e0b", size = 20342032, upload-time = "2026-02-23T00:21:09.904Z" },
    { url = "https://files.pythonhosted.org/packages/c9/35/2c342897c00775d688d8ff3987aced3426858fd89d5a0e26e020b660b301/scipy-1.17.1-cp314-cp314-macosx_14_0_x86_64.whl", hash = "sha256:7bdf2da170b67fdf10bca777614b1c7d96ae3ca5794fd9587dce41eb2966e866", size = 22678766, upload-time = "2026-02-23T00:21:14.313Z" },
    { url = "https://files.pythonhosted.org/packages/ef/f2/7cdb8eb308a1a6ae1e19f945913c82c23c0c442a462a46480ce487fdc0ac/scipy-1.17.1-cp314-cp314-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:adb2642e060a6549c343603a3851ba76ef0b74cc8c079a9a58121c7ec9fe2350", size = 32957007, upload-time = "2026-02-23T00:21:19.663Z" },
    { url = "https://files.pythonhosted.org/packages/0b/2e/7eea398450457ecb54e18e9d10110993fa65561c4f3add5e8eccd2b9cd41/scipy-1.17.1-cp314-cp314-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:eee2cfda04c00a857206a4330f0c5e3e56535494e30ca445eb19ec624ae75118", size = 35221333, upload-time = "2026-02-23T00:21:25.278Z" },
    { url = "https://files.pythonhosted.org/packages/d9/77/5b8509d03b77f093a0d52e606d3c4f79e8b06d1d38c441dacb1e26cacf46/scipy-1.17.1-cp314-cp314-musllinux_1_2_aarch64.whl", hash = "sha256:d2650c1fb97e184d12d8ba010493ee7b322864f7d3d00d3f9bb97d9c21de4068", size = 35042066, upload-time = "2026-02-23T00:21:31.358Z" },
    { url = "https://files.pythonhosted.org/packages/f9/df/18f80fb99df40b4070328d5ae5c596f2f00fffb50167e31439e932f29e7d/scipy-1.17.1-cp314-cp314-musllinux_1_2_x86_64.whl", hash = "sha256:08b900519463543aa604a06bec02461558a6e1cef8fdbb8098f77a48a83c8118", size = 37612763, upload-time = "2026-02-23T00:21:37.247Z" },
    { url = "https://files.pythonhosted.org/packages/4b/39/f0e8ea762a764a9dc52aa7dabcfad51a354819de1f0d4652b6a1122424d6/scipy-1.17.1-cp314-cp314-win_amd64.whl", hash = "sha256:3877ac408e14da24a6196de0ddcace62092bfc12a83823e92e49e40747e52c19", size = 37290984, upload-time = "2026-02-23T00:22:35.023Z" },
    { url = "https://files.pythonhosted.org/packages/7c/56/fe201e3b0f93d1a8bcf75d3379affd228a63d7e2d80ab45467a74b494947/scipy-1.17.1-cp314-cp314-win_arm64.whl", hash = "sha256:f8885db0bc2bffa59d5c1b72fad7a6a92d3e80e7257f967dd81abb553a90d293", size = 25192877, upload-time = "2026-02-23T00:22:39.798Z" },
    { url = "https://files.pythonhosted.org/packages/96/ad/f8c414e121f82e02d76f310f16db9899c4fcde36710329502a6b2a3c0392/scipy-1.17.1-cp314-cp314t-macosx_10_14_x86_64.whl", hash = "sha256:1cc682cea2ae55524432f3cdff9e9a3be743d52a7443d0cba9017c23c87ae2f6", size = 31949750, upload-time = "2026-02-23T00:21:42.289Z" },
    { url = "https://files.pythonhosted.org/packages/7c/b0/c741e8865d61b67c81e255f4f0a832846c064e426636cd7de84e74d209be/scipy-1.17.1-cp314-cp314t-macosx_12_0_arm64.whl", hash = "sha256:2040ad4d1795a0ae89bfc7e8429677f365d45aa9fd5e4587cf1ea737f927b4a1", size = 28585858, upload-time = "2026-02-23T00:21:47.706Z" },
    { url = "https://files.pythonhosted.org/packages/ed/1b/3985219c6177866628fa7c2595bfd23f193ceebbe472c98a08824b9466ff/scipy-1.17.1-cp314-cp314t-macosx_14_0_arm64.whl", hash = "sha256:131f5aaea57602008f9822e2115029b55d4b5f7c070287699fe45c661d051e39", size = 20757723, upload-time = "2026-02-23T00:21:52.039Z" },
    { url = "https://files.pythonhosted.org/packages/c0/19/2a04aa25050d656d6f7b9e7b685cc83d6957fb101665bfd9369ca6534563/scipy-1.17.1-cp314-cp314t-macosx_14_0_x86_64.whl", hash = "sha256:9cdc1a2fcfd5c52cfb3045feb399f7b3ce822abdde3a193a6b9a60b3cb5854ca", size = 23043098, upload-time = "2026-02-23T00:21:56.185Z" },
    { url = "https://files.pythonhosted.org/packages/86/f1/3383beb9b5d0dbddd030335bf8a8b32d4317185efe495374f134d8be6cce/scipy-1.17.1-cp314-cp314t-manylinux_2_27_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:6e3dcd57ab780c741fde8dc68619de988b966db759a3c3152e8e9142c26295ad", size = 33030397, upload-time = "2026-02-23T00:22:01.404Z" },
    { url = "https://files.pythonhosted.org/packages/41/68/8f21e8a65a5a03f25a79165ec9d2b28c00e66dc80546cf5eb803aeeff35b/scipy-1.17.1-cp314-cp314t-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl", hash = "sha256:a9956e4d4f4a301ebf6cde39850333a6b6110799d470dbbb1e25326ac447f52a", size = 35281163, upload-time = "2026-02-23T00:22:07.024Z" },
    { url = "https://files.pythonhosted.org/packages/84/8d/c8a5e19479554007a5632ed7529e665c315ae7492b4f946b0deb39870e39/scipy-1.17.1-cp314-cp314t-musllinux_1_2_aarch64.whl", hash = "sha256:a4328d245944d09fd639771de275701ccadf5f781ba0ff092ad141e017eccda4", size = 35116291, upload-time = "2026-02-23T00:22:12.585Z" },
    { url = "https://files.pythonhosted.org/packages/52/52/e57eceff0e342a1f50e274264ed47497b59e6a4e3118808ee58ddda7b74a/scipy-1.17.1-cp314-cp314t-musllinux_1_2_x86_64.whl", hash = "sha256:a77cbd07b940d326d39a1d1b37817e2ee4d79cb30e7338f3d0cddffae70fcaa2", size = 37682317, upload-time = "2026-02-23T00:22:18.513Z" },
    { url = "https://files.pythonhosted.org/packages/11/2f/b29eafe4a3fbc3d6de9662b36e028d5f039e72d345e05c250e121a230dd4/scipy-1.17.1-cp314-cp314t-win_amd64.whl", hash = "sha256:eb092099205ef62cd1782b006658db09e2fed75bffcae7cc0d44052d8aa0f484", size = 37345327, upload-time = "2026-02-23T00:22:24.442Z" },
    { url = "https://files.pythonhosted.org/packages/07/39/338d9219c4e87f3e708f18857ecd24d22a0c3094752393319553096b98af/scipy-1.17.1-cp314-cp314t-win_arm64.whl", hash = "sha256:200e1050faffacc162be6a486a984a0497866ec54149a01270adc8a59b7c7d21", size = 25489165, upload-time = "2026-02-23T00:22:29.563Z" },
]

[[package]]
name = "six"
version = "1.17.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/94/e7/b2c673351809dca68a0e064b6af791aa332cf192da575fd474ed7d6f16a2/six-1.17.0.tar.gz", hash = "sha256:ff70335d468e7eb6ec65b95b99d3a2836546063f63acc5171de367e834932a81", size = 34031, upload-time = "2024-12-04T17:35:28.174Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/b7/ce/149a00dd41f10bc29e5921b496af8b574d8413afcd5e30dfa0ed46c2cc5e/six-1.17.0-py2.py3-none-any.whl", hash = "sha256:4721f391ed90541fddacab5acf947aa0d3dc7d27b2e1e8eda2be8970586c3274", size = 11050, upload-time = "2024-12-04T17:35:26.475Z" },
]

[[package]]
name = "stack-data"
version = "0.6.3"
source = { registry = "https://pypi.org/simple" }
dependencies = [
    { name = "asttokens" },
    { name = "executing" },
    { name = "pure-eval" },
]
sdist = { url = "https://files.pythonhosted.org/packages/28/e3/55dcc2cfbc3ca9c29519eb6884dd1415ecb53b0e934862d3559ddcb7e20b/stack_data-0.6.3.tar.gz", hash = "sha256:836a778de4fec4dcd1dcd89ed8abff8a221f58308462e1c4aa2a3cf30148f0b9", size = 44707, upload-time = "2023-09-30T13:58:05.479Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/f1/7b/ce1eafaf1a76852e2ec9b22edecf1daa58175c090266e9f6c64afcd81d91/stack_data-0.6.3-py3-none-any.whl", hash = "sha256:d5558e0c25a4cb0853cddad3d77da9891a08cb85dd9f9f91b9f8cd66e511e695", size = 24521, upload-time = "2023-09-30T13:58:03.53Z" },
]

[[package]]
name = "threadpoolctl"
version = "3.6.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/b7/4d/08c89e34946fce2aec4fbb45c9016efd5f4d7f24af8e5d93296e935631d8/threadpoolctl-3.6.0.tar.gz", hash = "sha256:8ab8b4aa3491d812b623328249fab5302a68d2d71745c8a4c719a2fcaba9f44e", size = 21274, upload-time = "2025-03-13T13:49:23.031Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/32/d5/f9a850d79b0851d1d4ef6456097579a9005b31fea68726a4ae5f2d82ddd9/threadpoolctl-3.6.0-py3-none-any.whl", hash = "sha256:43a0b8fd5a2928500110039e43a5eed8480b918967083ea48dc3ab9f13c4a7fb", size = 18638, upload-time = "2025-03-13T13:49:21.846Z" },
]

[[package]]
name = "tornado"
version = "6.5.5"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/f8/f1/3173dfa4a18db4a9b03e5d55325559dab51ee653763bb8745a75af491286/tornado-6.5.5.tar.gz", hash = "sha256:192b8f3ea91bd7f1f50c06955416ed76c6b72f96779b962f07f911b91e8d30e9", size = 516006, upload-time = "2026-03-10T21:31:02.067Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/59/8c/77f5097695f4dd8255ecbd08b2a1ed8ba8b953d337804dd7080f199e12bf/tornado-6.5.5-cp39-abi3-macosx_10_9_universal2.whl", hash = "sha256:487dc9cc380e29f58c7ab88f9e27cdeef04b2140862e5076a66fb6bb68bb1bfa", size = 445983, upload-time = "2026-03-10T21:30:44.28Z" },
    { url = "https://files.pythonhosted.org/packages/ab/5e/7625b76cd10f98f1516c36ce0346de62061156352353ef2da44e5c21523c/tornado-6.5.5-cp39-abi3-macosx_10_9_x86_64.whl", hash = "sha256:65a7f1d46d4bb41df1ac99f5fcb685fb25c7e61613742d5108b010975a9a6521", size = 444246, upload-time = "2026-03-10T21:30:46.571Z" },
    { url = "https://files.pythonhosted.org/packages/b2/04/7b5705d5b3c0fab088f434f9c83edac1573830ca49ccf29fb83bf7178eec/tornado-6.5.5-cp39-abi3-manylinux1_x86_64.manylinux_2_28_x86_64.manylinux_2_5_x86_64.whl", hash = "sha256:e74c92e8e65086b338fd56333fb9a68b9f6f2fe7ad532645a290a464bcf46be5", size = 447229, upload-time = "2026-03-10T21:30:48.273Z" },
    { url = "https://files.pythonhosted.org/packages/34/01/74e034a30ef59afb4097ef8659515e96a39d910b712a89af76f5e4e1f93c/tornado-6.5.5-cp39-abi3-manylinux2014_aarch64.manylinux_2_17_aarch64.manylinux_2_28_aarch64.whl", hash = "sha256:435319e9e340276428bbdb4e7fa732c2d399386d1de5686cb331ec8eee754f07", size = 448192, upload-time = "2026-03-10T21:30:51.22Z" },
    { url = "https://files.pythonhosted.org/packages/be/00/fe9e02c5a96429fce1a1d15a517f5d8444f9c412e0bb9eadfbe3b0fc55bf/tornado-6.5.5-cp39-abi3-musllinux_1_2_aarch64.whl", hash = "sha256:3f54aa540bdbfee7b9eb268ead60e7d199de5021facd276819c193c0fb28ea4e", size = 448039, upload-time = "2026-03-10T21:30:53.52Z" },
    { url = "https://files.pythonhosted.org/packages/82/9e/656ee4cec0398b1d18d0f1eb6372c41c6b889722641d84948351ae19556d/tornado-6.5.5-cp39-abi3-musllinux_1_2_x86_64.whl", hash = "sha256:36abed1754faeb80fbd6e64db2758091e1320f6bba74a4cf8c09cd18ccce8aca", size = 447445, upload-time = "2026-03-10T21:30:55.541Z" },
    { url = "https://files.pythonhosted.org/packages/5a/76/4921c00511f88af86a33de770d64141170f1cfd9c00311aea689949e274e/tornado-6.5.5-cp39-abi3-win32.whl", hash = "sha256:dd3eafaaeec1c7f2f8fdcd5f964e8907ad788fe8a5a32c4426fbbdda621223b7", size = 448582, upload-time = "2026-03-10T21:30:57.142Z" },
    { url = "https://files.pythonhosted.org/packages/2c/23/f6c6112a04d28eed765e374435fb1a9198f73e1ec4b4024184f21faeb1ad/tornado-6.5.5-cp39-abi3-win_amd64.whl", hash = "sha256:6443a794ba961a9f619b1ae926a2e900ac20c34483eea67be4ed8f1e58d3ef7b", size = 448990, upload-time = "2026-03-10T21:30:58.857Z" },
    { url = "https://files.pythonhosted.org/packages/b7/c8/876602cbc96469911f0939f703453c1157b0c826ecb05bdd32e023397d4e/tornado-6.5.5-cp39-abi3-win_arm64.whl", hash = "sha256:2c9a876e094109333f888539ddb2de4361743e5d21eece20688e3e351e4990a6", size = 448016, upload-time = "2026-03-10T21:31:00.43Z" },
]

[[package]]
name = "traitlets"
version = "5.14.3"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/eb/79/72064e6a701c2183016abbbfedaba506d81e30e232a68c9f0d6f6fcd1574/traitlets-5.14.3.tar.gz", hash = "sha256:9ed0579d3502c94b4b3732ac120375cda96f923114522847de4b3bb98b96b6b7", size = 161621, upload-time = "2024-04-19T11:11:49.746Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/00/c0/8f5d070730d7836adc9c9b6408dec68c6ced86b304a9b26a14df072a6e8c/traitlets-5.14.3-py3-none-any.whl", hash = "sha256:b74e89e397b1ed28cc831db7aea759ba6640cb3de13090ca145426688ff1ac4f", size = 85359, upload-time = "2024-04-19T11:11:46.763Z" },
]

[[package]]
name = "tzdata"
version = "2026.2"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/ba/19/1b9b0e29f30c6d35cb345486df41110984ea67ae69dddbc0e8a100999493/tzdata-2026.2.tar.gz", hash = "sha256:9173fde7d80d9018e02a662e168e5a2d04f87c41ea174b139fbef642eda62d10", size = 198254, upload-time = "2026-04-24T15:22:08.651Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/ce/e4/dccd7f47c4b64213ac01ef921a1337ee6e30e8c6466046018326977efd95/tzdata-2026.2-py2.py3-none-any.whl", hash = "sha256:bbe9af844f658da81a5f95019480da3a89415801f6cc966806612cc7169bffe7", size = 349321, upload-time = "2026-04-24T15:22:05.876Z" },
]

[[package]]
name = "wcwidth"
version = "0.6.0"
source = { registry = "https://pypi.org/simple" }
sdist = { url = "https://files.pythonhosted.org/packages/35/a2/8e3becb46433538a38726c948d3399905a4c7cabd0df578ede5dc51f0ec2/wcwidth-0.6.0.tar.gz", hash = "sha256:cdc4e4262d6ef9a1a57e018384cbeb1208d8abbc64176027e2c2455c81313159", size = 159684, upload-time = "2026-02-06T19:19:40.919Z" }
wheels = [
    { url = "https://files.pythonhosted.org/packages/68/5a/199c59e0a824a3db2b89c5d2dade7ab5f9624dbf6448dc291b46d5ec94d3/wcwidth-0.6.0-py3-none-any.whl", hash = "sha256:1a3a1e510b553315f8e146c54764f4fb6264ffad731b3d78088cdb1478ffbdad", size = 94189, upload-time = "2026-02-06T19:19:39.646Z" },
]



================================================
FILE: .python-version
================================================
3.12



================================================
FILE: ML/Binarization.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
二值化(Binarization)
其核心思想就是把数据变成0和1
比如：
预测学生分数是否及格
我们可以使用Binarizer，设定一个阈值(Threshold) = 59.9（如果设定为60，那么60分也会被归为0）
大于59.9的，全部强行变成1
小于等于59.9的，全部强行变成0
"""

import numpy as np
from sklearn.preprocessing import Binarizer
# Binarizer 是一个class

# scikit-learn 的预处理工具通常要求输入二维数组
scores = np.array([
    [45], 
    [60], 
    [85], 
    [95], 
    [59]
])

# 使用flatten()函数，将多维数据（如矩阵，张量）“拍扁”成一维数组
# 它会按顺序读取源数据中的每一个元素，并把它们排成一排
print("原始分数：\n", scores.flatten())

binarizer = Binarizer(threshold=59.9)

scores_binarized = binarizer.fit_transform(scores)

print("\n二值化后的结果 (1 代表及格，0 代表不及格)：\n", scores_binarized.flatten())
# Output:
#   原始分数：

#    [45 60 85 95 59]

#   

#   二值化后的结果 (1 代表及格，0 代表不及格)：

#    [0 1 1 1 0]




================================================
FILE: ML/classification&regression.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
分类和回归的初步概念
"""

"""
分类(classification)（做单选题或多选题）
其核心目标是预测一个明确的“类别”或”标签“
比如：
医疗诊断：根据病人的血液指标，判断肿瘤是“良性”还是“恶性”
图像识别：给模型看一张照片，让它判断图片里是“猫”、“狗”还是“兔子”
电商推荐：预测一个用户会不会点击某个广告（“会”或“不会”）。
"""

"""
回归(regression)（做填空题）
其核心目标是预测一个连续的”数值“
比如：
天气预报：根据今天的湿度和气压，预测明天的精确气温是“28.5度”。
网约车估价：根据上车点和下车点的距离、当前路况，计算出这趟行程需要“45.5元”。
销售额预测：一家奶茶店根据历史数据和即将到来的节假日，预测下个月的营业额是“150,000元”。
"""

"""
总之一句话：分类是根据已知的数据进行“判断或者是做出选择”；回归是根据已知的数据进行“预测计算所求数据”
"""

"""
分类算法
逻辑回归(Logistic Regression)
Sigmoid 函数
![image.png](attachment:image.png)
用Gradient_Descent.ipynb中提到的y = w*x + b，将y算出后代入sigmoid函数中的Z
如果Z是极其巨大的正数，压缩出来无限接近于1，反之无限接近于0
通常会设定一个阈值，来判定最后的结果是1还是0
概率>=0.5，预测结果为1
概率<=0.5，预测结果为0
"""

from sklearn.linear_model import LogisticRegression
import numpy as np

X_train = np.array([
    [22, 7.25],   # 乘客 A：22岁，屌丝票价 7.25磅
    [38, 71.28],  # 乘客 B：38岁，土豪票价 71.28磅
    [26, 7.92],   # 乘客 C：26岁，屌丝票价 7.92磅
    [35, 53.10]   # 乘客 D：35岁，中产票价 53.10磅
])
y_train = np.array([0,1,0,1])

model = LogisticRegression()
model.fit(X_train, y_train)

Jack_features = np.array([[20, 0.0]])
jack_survived = model.predict(Jack_features)
print(f"机器给杰克的最终判决：{jack_survived[0]} (0:遇难, 1:生还)")
# 下面一行就是sigmoid函数给出的结果
jack_p = model.predict_proba(Jack_features)
print(f"机器算出的底层概率：遇难概率 {jack_p[0][0]:.2f}，生还概率 {jack_p[0][1]:.2f}")
# Output:
#   机器给杰克的最终判决：0 (0:遇难, 1:生还)

#   机器算出的底层概率：遇难概率 1.00，生还概率 0.00




================================================
FILE: ML/cross_validation.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
交叉验证(Cross Validation)
定义：交叉验证是一种评估机器学习模型泛化能力的方法，它将原始数据集切分成多个无交集的子集，在每一轮评估中，将其中一个子集作为验证集，剩下的子集都作为训练集来训练模型，重复此过程，直到每个子集都被用作过一次验证集（每一个子集轮流做验证集，轮流坐庄）。最后，对所有轮次的评估成果取平均，作为该模型性能的最终期望。

该方法有三个作用
第一：最大化减小运气的作用
如果在切分数据时，碰巧把所有噪音都切进了验证集，模型的判断结果就会很糟糕。交叉验证通过求平均值，最大化减小了运气所带来的影响
第二：最大化利用数据集
如果数据量过少（只有100条），如果按照传统的切分（20条当验证集，80条当训练集），模型就只能用80条数据学习，效果会很不理想
如果使用交叉验证，经过轮换，这100条就都可以被用于训练和验证
第三：辅助挑选最稳定的超参数
调参是，我们不再看单次验证集的分数，而是看交叉验证的平均分。平均分最高的超参数，说明模型的泛化能力最强

交叉验证分为三种方法
K折交叉验证(K-Fold CV)
把数据平均切成K份，适用于绝大多数普通的结构化数据
分层交叉验证(Stratified K-Fold CV)
在K折的基础上加上了一个条件——保证每一份的不同标签的比例和总体一致，适用于类别极度不平衡的数据
比如：
预测癌症（950 个健康，50 个癌症）。如果用普通的 K 折盲切，可能某一份里 100% 都是健康人，模型根本考不出水平。分层切法能保证每一折里，都均匀包含那个可怜的癌症样本。
留一法交叉验证(Leave-One-Out CV / LOOCV)
假设有N条数据，那就切成N份，每一份就用一条数据作为验证，剩下的N-1条全部拿去训练，适用于数据量极小的场景，但如果数据量大，计算量就会很大
"""

from sklearn.datasets import load_breast_cancer
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import cross_val_score
import numpy as np

data = load_breast_cancer()
X = data.data
y = data.target

model = RandomForestClassifier(max_depth=5, random_state=42)

print("🚀 开始执行 5折交叉验证...")

# cv=5 表示分成5份，它会自动帮你把X和y分成5份，轮流考5次
scores = cross_val_score(model, X, y, cv = 5)
print(f"\n📝 5 次模拟考的具体成绩: {scores}")

print(f"🎯 最终平均分 (模型真正的实力): {np.mean(scores):.4f}")
print(f"📊 成绩波动标准差 (越小说明模型越稳定): {np.std(scores):.4f}")
# Output:
#   🚀 开始执行 5折交叉验证...

#   

#   📝 5 次模拟考的具体成绩: [0.92105263 0.93859649 0.98245614 0.97368421 0.98230088]

#   🎯 最终平均分 (模型真正的实力): 0.9596

#   📊 成绩波动标准差 (越小说明模型越稳定): 0.0252




================================================
FILE: ML/depth_UF_OF_GF.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
深度(depth)
所谓的深度，就是模型为了得出一个结论，最多被允许问几个问题

如果深度太浅（问题过少），信息量太少了，就会导致欠拟合
如果深度刚刚好（涵盖的问题正好问到重点并且核心），完美泛化
如果深度太深（问题太多了），会引入不必要的噪音，就会导致过拟合
"""

"""
欠拟合(Underfitting)
模型学习的数据太少，或者模型本身的学习能力很差，训练集和验证集的得分很低

过拟合(Overfitting)
模型的学习能力太强，学习的范围太广，甚至包含了一些噪音，导致泛化能力弱，死记硬背，不理解真正的解题逻辑，训练集分数高，但是验证集分数很差

适度拟合(Good Fit)
模型学习了数据的规律，学到要点和核心，同时又避开了大部分的噪音，泛化能力强，训练集和测试集分数都很高
"""



================================================
FILE: ML/Ensemble_Learning.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
集成学习；使用多个小模型，针对于已知的训练集给出更精准的答案
这些小模型看不同特征，来得出结果（原理类似于MoE架构）

RandomForestClassifier是一种基于集成学习(ensemble learning)的强大算法
生成多个决策树，看不同的特征来得出结果，少数服从多数，增加容错率
比如：
有三个人帮我挑甜瓜
A（敲瓜）：只听声音
B（看纹理）：只看瓜皮纹路清不清晰
C（看瓜蔓）：只看瓜藤卷不卷
D（看产地）：只看瓜的产地在哪
当我拿起一个西瓜时
A看声音（被厚皮骗了）：投了“不甜”（-1）
B看重量（发现很沉）：投了“甜”（+1）
C看瓜藤（发现还很健壮）：投了“甜”（+1）
D看产地（发现是新疆瓜）：投了“甜”（+1）
这就是为什么通过集成学习，能够提高判断的正确率

集成学习是极其有必要的，因为在人类的常识中，掌握的信息越多，做出的判断就越准。
但是在真实开发环境中，我们拿到的数据，其实纯度是非常低的（有用的信息很少），也就是说，单模型会因为在进行model.fit()中，总结出的公式的element是包含所有噪音的，导致模型会认为，这些噪音也是有用的判别依据，所以在测试的时候，就有可能判断错误；而多模型是只看部分特征的，这意味着这些模型做出的判断当中，噪音所起到的作用会降低，做出的判断就会更加准确
"""



================================================
FILE: ML/feature_scaling.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
特征缩放(Feature Scaling)
概念：是机器学习中的一种数据预处理技术，旨在将不同量纲（单位）或者是数据范围内的原始数据调整到统一的尺度上，也就是说，就是把所有特征的数值范围强行按比例拉平

比如：
假设我们要让机器学习模型来判断两个人的体型是不是差不多
模型只能看到两个数据（特征）：
1. 身高（单位是m）：比如1.70m
2. 体重（单位是g）：比如70000g（也就是70kg）
现在有三个人
小明：身高1.70m，体重70000g（70kg）
小红：身高1.80m，体重70000g（70kg）
小刚：身高1.70m，体重70100g（70.1kg）
不难看出，小明和小刚的体型几乎是一模一样的，而小红比他们高很多，体型差异很大
但是，模型在训练的时候，会认为：
小明和小红的身高差了0.1，体重差了0。总差异算作0.1
小明和小刚的身高差了0，体重差了100，总差异算作100
于是，模型会得出这样一个结论：小明和小红的体型差距非常小，小明和小航的体型差距非常大，这种结论很显然是错的
为了解决这个问题，我们得要用到一个数据预处理技术，也就是特征缩放
"""

"""
在scikit-learn中，特征缩放有三种方式：
标准化(StandardScaler)
归一化(MinMaxScaler)
正则化(Normalizer)
上述三种class都是在sklearn.preprocessing这个工具箱里面
下面先讲标准化
"""

"""
标准化的计算方法是：算出所有数据的平均值，然后再计算标准差（用每一个原始数据减去平均值，然后将这个差值平方，将所有差值的平方加起来，再除以总个数，得到方差，再对方差进行开平方），最后带入公式：新数值 = （原始数据-平均值）/ 标准差
"""

from sklearn.preprocessing import StandardScaler # StandardScaler 是一个类

# 1. 召唤“公平秤”工具
scaler = StandardScaler()

# 2. 对“复习资料”（训练集）进行缩放
# fit_transform 的意思是：先去计算训练集的平均值和标准差(fit)，然后用刚才算出来的平均值作为标准，把大家的数据都去按照比例放缩(transform)
X_train_scaled = scaler.fit_transform(X_train)

# 3. 对“考卷”（测试集）进行缩放
# 注意这里只有 transform。因为模型是根据在平时的学习训练中，按照在训练集的标准来找规律的，如果在测试集中又新算出平均值，容易乱套（比例对不上），那就体现不出模型在平时训练中的表现了
# 要牢记，机器学习的本质就是在已知中训练，去解决未知的问题
X_test_scaled = scaler.transform(X_test)

"""
将这个文件中涉及到的代码知识点和supervised_learning.ipynb中的结合起来，就能够得出一套完整的模型训练流水线（缺少调参环节，也就是验证集）
"""

import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.ensemble import RandomForestClassifier # 详情请看Ensemble_Learning.ipynb文件
from sklearn.metrics import accuracy_score

# 特征X：重量（kg），跑分，续航（h）
X = np.array([
    [3.5, 15000, 2.0],  # 游戏本
    [1.2,  4000, 10.0], # 轻薄本
    [2.8, 12000, 3.5],  # 全能本
    [3.2, 16000, 1.5],  # 游戏本
    [1.0,  3500, 12.0]  # 轻薄本
])

# 标签 y：1（是游戏本），0（不是）
y = np.array([1, 0, 0, 1, 0])

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

scaler = StandardScaler()
X_train_scaled = scaler.fit_transform(X_train)
X_test_scaled = scaler.transform(X_test)

model = RandomForestClassifier(random_state=42)

# model.fit() 的意思是：使用训练集的特征和标签来拟合模型，总结公式
model.fit(X_train_scaled, y_train)

# model.predict() 的意思是：使用训练好的模型，对测试集特征进行预测，并将结果存入变量中
# 返回的结果是一个numpy数组(np.ndarray)，就跟普通列表一样（使用方法），但是计算更快
predictions = model.predict(X_test_scaled)

print(f"模型的预测答案：{predictions}")
print(f"真实的正确答案：{y_test}")
print(f"模型准确率：{accuracy_score(y_test, predictions) * 100}%")
# Output:
#   模型的预测答案：[0]

#   真实的正确答案：[0]

#   模型准确率：100.0%


"""
归一化的计算方法是：把所有的数据，强行按比例挤压到一个固定的箱子里，通常是0-1
比如：
假设一次考试，满分是150分，全班最高考了150分，最低考了50分
考 50 分的人，进度条是 0%（对应数字 0）
考 150 分的人，进度条是 100%（对应数字 1）
考 100 分的人，刚好在最低和最高的最中间，进度条是 50%（对应数字 0.5）
新数值 = （当前数值-最小值）/（最大值-最小值）
它的特点是具有“强边界”，缩放后，数据绝对不可能小于0，也绝对不可能大于1
而标准化的特点是：寻找数据的“重心“（平均值），看看每个数据偏离重心的距离
同样是那场考试，平均分是100分
考 100 分的人，刚好是平均水平，所以他的新数值是 0
考 120 分的人，比平均分高，新数值可能是 +1.5
考 80 分的人，比平均分低，新数值可能是 -1.5

归一化的代码写法跟标准化完全一致
"""

"""
怎么选择
大多数场景选择标准化，但如果当对输入范围有严格要求时，归一化效果更好
"""

"""
正则化(Normalizer)主要是按行缩放。严格来说，是样本缩放(Sample Scaling)，把这一行的全部特征压缩成一个长度为1的向量
代码写法跟前两种完全一致
"""



================================================
FILE: ML/Gradient_Descent.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
梯度下降(Gradient Descent)是一种迭代求函数最小值的算法
也就是说，一步一步往最低处挪，慢慢找到最优解

比如：
一个人站在山坡上，目标是走到山谷最低点
梯度：当前位置最陡的上坡方向
负梯度：最陡的下坡方向（我们要走的方向）
学习率(Learning Rate)：每一步迈多大
操作：每次都往最陡下坡走一小步，反复走，最终走到谷底

当前的坐标（经纬度） = 模型当前的参数，比如$w$ 和 $b$，如果这个人在这个(w,b)坐标，就意味着模型已经到了最优状态
"""

"""
损失函数(Loss Function)
衡量模型预测结果好不好，值越小，模型的预测越准确，而我们的目标，就是求损失函数的最小值

梯度(Gradient)
函数在当前点的变化率，由导数/偏导数组成，指向函数上升最快的方向

负梯度(Negative Gradient)
函数下降最快的方向，梯度下降的移动方向

学习率(Learning Rate)
是一个超参数。每次移动的步长，如果步长太大，就会错过最低点；如果步长太小，就会导致训练时间极长
"""

import numpy as np

x_dat = np.array([1, 2, 3])      # 公里数
y_tru = np.array([12, 14, 16])   # 真实收费 (根据 2x+10 算出来的)

w = 0.0
b = 0.0

learning_rate = 0.1
epochs = 500

for i in range(epochs):
    y_pred = w * x_dat + b
    loss = np.mean((y_tru - y_pred) ** 2)

    N = len(x_dat)
    grad_w = -(2/N) * np.sum(x_dat * (y_tru - y_pred))
    grad_b = -(2/N) * np.sum(y_tru - y_pred)

    w = w - learning_rate * grad_w
    b = b - learning_rate * grad_b

    if (i + 1) % 10 == 0:
        print(f"走了 {i+1} 步 | 误差(Loss): {loss:.4f} | 当前位置: w={w:.2f}, b={b:.2f}")

print("\n🎉 到达谷底！模型训练完毕！")
print(f"机器最终学到的公式：y = {w:.2f}x + {b:.2f}")
# Output:
#   走了 10 步 | 误差(Loss): 5.4057 | 当前位置: w=4.64, b=4.01

#   走了 20 步 | 误差(Loss): 3.3228 | 当前位置: w=4.07, b=5.30

#   走了 30 步 | 误差(Loss): 2.0424 | 当前位置: w=3.62, b=6.32

#   走了 40 步 | 误差(Loss): 1.2554 | 当前位置: w=3.27, b=7.11

#   走了 50 步 | 误差(Loss): 0.7717 | 当前位置: w=3.00, b=7.74

#   走了 60 步 | 误差(Loss): 0.4743 | 当前位置: w=2.78, b=8.23

#   走了 70 步 | 误差(Loss): 0.2916 | 当前位置: w=2.61, b=8.61

#   走了 80 步 | 误差(Loss): 0.1792 | 当前位置: w=2.48, b=8.91

#   走了 90 步 | 误差(Loss): 0.1102 | 当前位置: w=2.38, b=9.14

#   走了 100 步 | 误差(Loss): 0.0677 | 当前位置: w=2.29, b=9.33

#   走了 110 步 | 误差(Loss): 0.0416 | 当前位置: w=2.23, b=9.47

#   走了 120 步 | 误差(Loss): 0.0256 | 当前位置: w=2.18, b=9.59

#   走了 130 步 | 误差(Loss): 0.0157 | 当前位置: w=2.14, b=9.68

#   走了 140 步 | 误差(Loss): 0.0097 | 当前位置: w=2.11, b=9.75

#   走了 150 步 | 误差(Loss): 0.0059 | 当前位置: w=2.09, b=9.80

#   走了 160 步 | 误差(Loss): 0.0037 | 当前位置: w=2.07, b=9.84

#   走了 170 步 | 误差(Loss): 0.0022 | 当前位置: w=2.05, b=9.88

#   走了 180 步 | 误差(Loss): 0.0014 | 当前位置: w=2.04, b=9.90

#   走了 190 步 | 误差(Loss): 0.0008 | 当前位置: w=2.03, b=9.92

#   走了 200 步 | 误差(Loss): 0.0005 | 当前位置: w=2.03, b=9.94

#   走了 210 步 | 误差(Loss): 0.0003 | 当前位置: w=2.02, b=9.95

#   走了 220 步 | 误差(Loss): 0.0002 | 当前位置: w=2.02, b=9.96

#   走了 230 步 | 误差(Loss): 0.0001 | 当前位置: w=2.01, b=9.97

#   走了 240 步 | 误差(Loss): 0.0001 | 当前位置: w=2.01, b=9.98

#   走了 250 步 | 误差(Loss): 0.0000 | 当前位置: w=2.01, b=9.98

#   走了 260 步 | 误差(Loss): 0.0000 | 当前位置: w=2.01, b=9.99

#   走了 270 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=9.99

#   走了 280 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=9.99

#   走了 290 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=9.99

#   走了 300 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=9.99

#   走了 310 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 320 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 330 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 340 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 350 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 360 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 370 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 380 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 390 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 400 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 410 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 420 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 430 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 440 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 450 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 460 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 470 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 480 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 490 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   走了 500 步 | 误差(Loss): 0.0000 | 当前位置: w=2.00, b=10.00

#   

#   🎉 到达谷底！模型训练完毕！

#   机器最终学到的公式：y = 2.00x + 10.00


"""
y = w*x + b

w代表权重(weight)
它代表了机器觉得这个特征对最终结果有多重要

x代表特征(Feature)

y代表标签(Label)

w和x的关系
w*x的本质，就是使用权重去放大，缩小甚至反转这个特征的影响力
机器通过改变w的大小和正负号，来决定这个特征的作用大小
abs(w)越大，机器就觉得这个特征就越重要，起到的作用就越大，反之，就越不重要，作用就越小
正数（正相关）
如果特征x越大，最终的y就越大
负数（负相关）
如果特征x越大，最终的y就越小
通俗来说：
绝对值大小决定了这个特征x是“主角”还是“跑龙套”
正负号决定了这个特征x是“奖励加分”还是“惩罚扣分”
"""

from sklearn.linear_model import SGDRegressor
import numpy as np

x_data = np.array([[1], [2], [3]])
y_true = np.array([12, 14, 16])

# SGDRegressor（随机梯度下降回归器），告诉程序，我们要解决的是预测具体数字（回归的问题），使用的工具是“梯度下降”
# learning_rate='constant' 的意思是，使用固定步长
# eta0=0.1 具体的步长大小（初始学习率），每次的步长是0.1
# max_iter=1000 最大迭代次数（训练次数）
model = SGDRegressor(learning_rate="constant", eta0=0.1, max_iter=1000, random_state=42)

model.fit(x_data, y_true)

# coef_ （coefficient/系数），是 w （权重weight）
# 在复杂模型中，权重可能有几百个（对应几百个特征），所以返回的是一个数组
# intercept_ 就是 b （偏置/截距bias）
# 只要是模型通过fit()训练后自己学到的属性，后面都会带一个下划线
w_learned = model.coef_[0]
b_learned = model.intercept_[0]

print(f"代码提取的公式：y = {w_learned:.2f}x + {b_learned:.2f}")
# Output:
#   代码提取的公式：y = 2.09x + 9.80




================================================
FILE: ML/HPO.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
调参(Hyperparameters Optimization, HPO)
在机器学习中，分为两种“参数”：参数和超参数

参数(Parameters)
定义：模型在读取训练数据(Train Set)的过程中，通过数学算法自动计算并学习出来的内部变量
用通俗语言讲，就是学生（模型）通过做作业（训练），自己总结在脑子里面的“知识点”
比如：模型发现“年龄大于50岁的人生还率低”，这个“50”就是它自己算出来的参数
工程师无法手动直接输入或修改这些值，参数是算法经过成千上万次迭代运算后，自己总结出的“规律的具象化”

超参数(Hyperparameters)
定义：模型在开始训练前，必须由工程师提前人为设定在整个训练过程中不会被算法自动计算、学习或修改的，用于约束模型学习行为、控制模型复杂度、指导整个训练流程的外部规则变量。
用通俗语言讲，就是老师（工程师）在学生（模型）开始写作业（训练）时、学生往脑子里总结知识点（参数）之前，老师提前给学生定下的一整套学习规则、学习边界、学习方法。这些规则，在学生写作业、学知识的全程都不能私自改动，却直接决定了学生能不能高效学到真正的解题逻辑，会不会只会死记硬背答案、最终面对没见过的新试卷（测试集）能不能考好
比如：
工程师提前订好“模型最多只能总结100条类似‘年龄大于50岁的人生还率低’的规律，不能无限制总结”，这个“100”就是超参数
工程师提前订好“模型每次发现自己预测错了，只能小幅度修正自己总结的知识点，不能全盘推翻之前的结论”，这个“修正的幅度”，就是超参数
老师提前规定的“这套作业最多刷5遍，刷够就停”，“每次错题最多只能修改3个知识点，不能把整本笔记全改掉”，“最多允许你记住40道题的固定答案，防止死记硬背”。这些提前规定，学生不能自己更改的学习规则，全都是超参数
"""



================================================
FILE: ML/metrics.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
评价指标对应的库就是sklearn.metrics
"""

"""
分类的评价指标通常有混淆矩阵(confusion matrix)、精确率(precision)、召回率(recall)、F1分数(f1 score)、和准确率(accuracy)
"""

"""
混淆矩阵的4种关系
假设你的模型是一个警察，目标是抓小偷 (预测为正例/1)，不抓好人 (预测为负例/0)
TP (True Positive - 真正例)： 警察认为他是小偷，他真的是小偷
TN (True Negative - 真负例)： 警察认为他是好人，他真的是好人
FP (False Positive - 假正例)： 警察认为他是小偷，但他是好人
FN (False Negative - 假负例)： 警察认为他是好人，但他其实是小偷
"""

"""
精确率(precision)
定义：在所有被预测为正的样本中实际为正的样本比例
在警察抓回来的所有人里，到底有百分之几是真正的小偷
precision = TP / (TP + FP) （宁漏不错）

召回率(recall)
定义：在实际为正的样本中被预测为正的样本
recall = TP / (TP + FN)
如果是预测癌症，召回率必须高（哪怕误诊让病人做一次活检，也绝对不能让一个真正的癌症患者漏网回家）（宁错不漏）

F1 分数(f1 score)
调和平均数。当模型的精确率和召回率冲突时，可以采用该指标来衡量模型的优劣
F1 = (2*p*r) / (p+r)
"""

from sklearn.metrics import confusion_matrix, precision_score, recall_score, f1_score, classification_report

y_true = [0, 0, 0, 0, 0, 0, 0, 1, 1, 1]

y_pred = [0, 0, 0, 0, 0, 1, 1, 1, 0, 0]

cm = confusion_matrix(y_true, y_pred)
print(cm)
# 输出格式通常是
# [[TN, FP]
#  [FN, TP]]

precision = precision_score(y_true, y_pred)
print(f"精确率 (Precision): {precision:.2f}")

recall = recall_score(y_true, y_pred)
print(f"召回率 (Recall): {recall:.2f}")

f1 = f1_score(y_true, y_pred)
print(f"F1 分数 (F1-Score): {f1:.2f}")

# classification_report 函数可以只通过一行代码来打印所有的评价指标（报表）
print(classification_report(y_true, y_pred, target_names=["好人(0)", "小偷(1)"]))
# Output:
#   [[5 2]

#    [2 1]]

#   精确率 (Precision): 0.33

#   召回率 (Recall): 0.33

#   F1 分数 (F1-Score): 0.33

#                 precision    recall  f1-score   support

#   

#          好人(0)       0.71      0.71      0.71         7

#          小偷(1)       0.33      0.33      0.33         3

#   

#       accuracy                           0.60        10

#      macro avg       0.52      0.52      0.52        10

#   weighted avg       0.60      0.60      0.60        10

#   


"""
回归的评价指标主要有平均绝对误差(Mean Absolute Error, MAE)、均方误差(Mean Squared Error, MSE)、均方根误差(Root Mean Squared Error, RMSE)
"""

"""
平均绝对误差
利用模型的预测值与真实值的差值来衡量，误差越小，回归模型的拟合程度就越好
![image.png](attachment:image.png)

均方误差
求误差的平方和，这也就意味着均方误差相比于平均绝对误差更敏感，更容易波动
![image-2.png](attachment:image-2.png)

均方根误差
对均方误差进行开平方运算（在MSE上加个根号），这样做既能保证单位的统一，同时又保留了均方误差的特性

绝对系数$R^2$ (Residuals-Squared)
MAE和RMSE有个缺点：没有上限。假如 MAE 算出来是 5000，这到底是好还是坏？如果是预测房价，差 5000 块简直是神仙模型；但如果是预测你明天的午餐费，差 5000 块就是灾难。
起到统一度量衡的作用
$R^2 = 1.0$：完美预言家，100% 预测正确
$R^2$ 在 0 到 1 之间：越接近 1 越好（比如 0.8 说明模型很优秀）。
$R^2 = 0$：预测效果差
$R^2 < 0$ (负数)：预测效果很差
"""

import numpy as np
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score

y_true = np.array([100, 150, 200, 250, 300])

y_pred = np.array([105, 145, 200, 270, 320])

mae = mean_absolute_error(y_true, y_pred)
print(f"1. MAE (平均绝对误差): {mae:.2f} 万元")

mse = mean_squared_error(y_true, y_pred)
print(f"2. MSE (均方误差): {mse:.2f}")

rmse = np.sqrt(mse)
print(f"3. RMSE (均方根误差): {rmse:.2f} 万元")

r2 = r2_score(y_true, y_pred)
print(f"4. R² 分数 (决定系数): {r2:.4f}")



================================================
FILE: ML/sklearn_dataset.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
对应的模块是：sklearn.datasets
"""

"""
sklearn中的内置数据集纯度极高，没有缺失值，不用考虑特征缩放，没有乱码。
sklearn数据集分为经典玩具数据集、真实世界数据集、人工生成数据集

经典玩具数据集（只有几百行）
鸢尾花数据集(load_iris)：根据花瓣的长度、宽度等四个特征，预测这朵花属于哪三个品种之一（经典多分类问题）
乳腺癌数据集(load_breast_cancer)：根据肿瘤的30个细胞特征，判断它是良性还是恶性（经典二分类问题）
糖尿病数据集(load_diabetes)：根据病人的年龄、性别、BMI等特征，预测一年后疾病的进展指数（经典回归问题）
手写数字数据集(load_digits)：8x8 像素的低分辨率手写数字图片(0-9)，用来做图像识别分类

真实世界数据集（有几万行，第一次调用会从网上下载）
加州放假数据集(fetch_california_housing)：根据经纬度、房龄、房间数，来预测街区的中位数房价（回归问题的进阶）
新闻组文本数据集(fetch_20newsgroups)：几万篇新闻文章，用来练习让机器读懂人类文字（自然语言处理）

人工生成数据集（可以用代码直接编出一些数据）
make_classification()：自动生成带有一点点噪音的分类数据
make_moons()：生成两团像弯月亮一样互相交错的数据点，专门用来测试模型画边界的问题
"""

"""
sklearn返回的数据是bunch对象（可以近似看作Python中的字典）
"""

from sklearn.datasets import load_breast_cancer
# load_breast_cancer 是一个class

cancer_data = load_breast_cancer()
X = cancer_data.data
y = cancer_data.target

print(f"这批数据共有 {X.shape[0]} 个病人，每个人有 {X.shape[1]} 个特征线索。")
print(f"前5个病人的真实诊断结果 (y): {y[:5]}")

print(f"\n特征名字 (X的列名): \n{cancer_data.feature_names[:5]}...") # 只打印前5个看看
print(f"标签名字 (y的含义): {cancer_data.target_names}")
# Output:
#   这批数据共有 569 个病人，每个人有 30 个特征线索。

#   前5个病人的真实诊断结果 (y): [0 0 0 0 0]

#   

#   特征名字 (X的列名): 

#   ['mean radius' 'mean texture' 'mean perimeter' 'mean area'

#    'mean smoothness']...

#   标签名字 (y的含义): ['malignant' 'benign']




================================================
FILE: ML/ML_introduction/Reinforcement_Learning.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
强化学习(Reinforcement Learning, RL)
定义：给模型一个任务，还有相应的奖惩制度，剩下的让模型自我训练

强化学习并不像其他三类监督学习那样有数据集。在强化学习中，数据是实时产生的交互轨迹
强化学习的“数据”其实是由一条条由以下内容组成的经验链
当前状态(status)→采取的动作(action)→获得的奖惩(reward)→变成的新状态(new status)
现代强化学习通常有一个“经验池”，把这些自己试出来的经验链存起来，然后反复从这些经验中学习哪些动作能拿高分
"""



================================================
FILE: ML/ML_introduction/semi-supervised_learning.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
半监督学习(Semi-supervised Learning)
定义：介于监督学习和无监督学习之间。在训练时使用少量有标签的数据和大量无标签的数据
在现实世界中，获取无标签数据非常容易且成本低廉，但是给数据打标签需要大量的人力和时间，所以我们可以往数据集里面加一点有标签的数据，让模型举一反三
"""



================================================
FILE: ML/ML_introduction/supervised_learning.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
机器学习主要分为四大类：监督学习(Supervised Learning)，半监督学习(Semi-supervised Learning)，无监督学习(Unsupervised Learning)，强化学习(Reinforcement Learning)
"""

"""
监督学习
概念：我们在训练这些模型的时候，给它的数据里面不仅有题目（特征），还有标准答案（标签）

特征是你用来描述一个事物的属性、指标或者是数据点
比如：当你向朋友描述一个人时，你会说“他身高1米8，戴眼镜，喜欢打篮球”。这里的“身高”、“是否戴眼镜”、“爱好”就是这个人的特征。
在机器学习中，特征通常被写成大写字母X，因为特征往往不止一个，他们组合在一起会形成一个”数据矩阵“（二维表格）

标签是你希望模型最终预测出来的结果。
在模型训练阶段，标签就是提供给模型的”标准答案“，让它知道自己猜的对不对。
比如：接上面的例子，如果你描述了那个人的特征，最后让你朋友猜“这人是程序员还是健身教练？”，那么“职业”就是你要预测的标签。
标签通常被写成字母y，因为对于每个事物来说，我们要预测的结果通常只有一个（比如房价是多少，是否有病），它在数据中通常只是一列数字

总之，特征就是一个事物的属性或者是特点（比如游戏本，特征是笨重，性能好，续航差）；标签就是我们希望模型能根据已知的数据，能给出预期的判断或者是数值答案（“分类”标签和“回归”标签）
"""

"""
在scikit-learn的工作流中，拿到数据后的第一件事，就是把数据拆分成复习资料（训练集）、模拟考（验证集）和考卷（测试集）
所对应的函数就是train_test_split
"""

import numpy as np
from sklearn.model_selection import train_test_split

# 重量，性能跑分，续航时长h
X = np.array([
    [3.5, 15000, 2.0],  # 电脑 A (游戏本)
    [1.2,  4000, 10.0], # 电脑 B (轻薄本)
    [2.8, 12000, 3.5],  # 电脑 C (全能本)
    [3.2, 16000, 1.5],  # 电脑 D (游戏本)
    [1.0,  3500, 12.0]  # 电脑 E (轻薄本)
])

y = np.array([1, 0, 0, 1, 0])


# ================= 第一步：分出绝对保密的“期末考” =================
# 我们把全部数据切开：80% 留作平时用(X_temp)，20% 锁进保险柜作为期末考(X_test)
# test_size=0.2 的意思是把20%的数据留作测试（考卷），80% 用来训练（复习）
# random_state=42 就像是游戏里的“固定存档”（种子数），保证每次运行拆分的结果都是一样的
# X_train, X_test, y_train, y_test 的顺序定死，千万不能更改顺序
# shuffle 关键词布尔值，True，打乱数据（默认）；False，不打乱数据
X_temp, X_test, y_temp, y_test = train_test_split(X, y, test_size = 0.2, random_state = 42)

# ================= 第二步：把平时用的数据分成“作业”和“模拟考” =================
# 注意这里的数学逻辑：我们要从剩下的 80% (temp) 里切出 25%。
# 因为 80% * 25% = 20%，这样刚好分出了占总数据 20% 的验证集
X_train, X_val, y_train, y_val = train_test_split(X_temp, y_temp, test_size=0.25, random_state=42)

print("给模型复习用的特征（X_train）：")
print(X_train)
print("\n给模型模拟考用的特征（X_val）：")
print(X_val)
print("\n留作考试用的特征(X_test)：")
print(X_test)

'''
给模型复习用的特征（X_train）：
[[3.2e+00 1.6e+04 1.5e+00]
 [1.0e+00 3.5e+03 1.2e+01]
 [3.5e+00 1.5e+04 2.0e+00]]

给模型模拟考用的特征（X_val）：
[[2.8e+00 1.2e+04 3.5e+00]]

留作考试用的特征(X_test)：
[[1.2e+00 4.0e+03 1.0e+01]]

这种输出结果是科学计数法（为了使排版整齐）
在编程中，e+03就代表e前面的这个数乘以10^3（也就是1000），e+00就是乘以10^0（也就是1，保持不变）
例如：
1.2e+00 = 1.2 x 10^0 = 1.2
4.0e+03 = 4.0 x 10^3 = 4000

将原来的数据集顺序打乱，然后按照test_size分配给训练、验证和测试
'''
# Output:
#   给模型复习用的特征（X_train）：

#   [[3.2e+00 1.6e+04 1.5e+00]

#    [1.0e+00 3.5e+03 1.2e+01]

#    [3.5e+00 1.5e+04 2.0e+00]]

#   

#   给模型模拟考用的特征（X_val）：

#   [[2.8e+00 1.2e+04 3.5e+00]]

#   

#   留作考试用的特征(X_test)：

#   [[1.2e+00 4.0e+03 1.0e+01]]

#   '\n给模型复习用的特征（X_train）：\n[[1.0e+00 3.5e+03 1.2e+01]\n [2.8e+00 1.2e+04 3.5e+00]\n [3.5e+00 1.5e+04 2.0e+00]\n [3.2e+00 1.6e+04 1.5e+00]]\n\n留作考试用的特征(X_test)：\n[[1.2e+00 4.0e+03 1.0e+01]]\n\n这种输出结果是科学计数法（为了使排版整齐）\n在编程中，e+03就代表e前面的这个数乘以10^3（也就是1000），e+00就是乘以10^0（也就是1，保持不变）\n例如：\n1.2e+00 = 1.2 x 10^0 = 1.2\n4.0e+03 = 4.0 x 10^3 = 4000\n\n将原来的数据集顺序打乱，然后按照test_size分配给训练和测试\n'

"""
验证集的最重要作用就是调参（寻找最佳超参数）
（调参请看HPO.ipynb文件）

验证集(Validation Set)
是指在模型训练过程中，从原始数据中拨出来的一份独立数据，他不参与模型的直接参数计算和训练，专门用于评估模型在未见数据上的表现（也就是泛化能力(Generalization Ability)），并据此进行超参数优化
如果不设验证集，直接用测试集来调整模型，就会发生极其严重的“数据泄露(Data Leakage)”。这意味着模型虽然在测试集上分数很高，但那是根据测试集测出来的判断结果修改超参数得到的，如果换一个测试集，就会导致模型在真实场景下的泛化表现大打折扣
换句话说，机器学习的本质，就是让机器在已知的数据中，去解决未知的问题。将验证集和测试集分开，就是为了让机器在已知（训练集）中，去解决未知（测试集）的问题，而模型训练中，需要人为干预，也就是调参，验证集就是干这个用的。
比如：
一名学生（模型），平时通过刷题（用训练集训练模型）来增强做题能力，然后学校会举行模拟考试（验证集），并且会告诉学生哪里做对了，哪里做错了，给予反馈（调参），然后学生就会再接着刷题（训练），学生再接着参加模拟考试，以此循环类推，最后学生参加高考（测试集），衡量一名学生的学业能力（机器的学习能力）
在机器学习竞赛中，衡量模型的学习能力也是通过只进行一次测试（测试集）来打分的。
"""

from sklearn.datasets import load_breast_cancer
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score

data = load_breast_cancer()
X = data.data
y = data.target

X_temp1, X_test1, y_temp1, y_test1 = train_test_split(X, y, test_size=0.2, random_state=42)
X_train1, X_val1, y_train1, y_val1 = train_test_split(X_temp1, y_temp1, test_size=0.25, random_state=42)

print(f"数据总数: {len(X)}")
print(f"训练集(平时): {len(X_train1)}, 验证集(模拟考): {len(X_val1)}, 测试集(高考): {len(X_test1)}\n")

depth_options = [1, 5, 20]

best_score = 0
best_depth = 0

for depth in depth_options:
    model = RandomForestClassifier(max_depth=depth, random_state=42)
    model.fit(X_train1, y_train1)

    val_pred = model.predict(X_val1)
    val_score = accuracy_score(y_val1, val_pred)

    print(f"尝试树深度={depth} | 验证集(模拟考)得分: {val_score:.4f}")

    if val_score > best_score:
        best_score = val_score
        best_depth = depth

print(f"\n模拟考结束！我们选定最佳超参数：max_depth = {best_depth}")

final_model = RandomForestClassifier(max_depth=best_depth, random_state=42)
final_model.fit(X_temp1, y_temp1)

test_pred = final_model.predict(X_test1)
test_score = accuracy_score(y_test1, test_pred)

print(f"模型最终的测试集(高考)真实成绩是: {test_score:.4f}")
# Output:
#   数据总数: 569

#   训练集(平时): 341, 验证集(模拟考): 114, 测试集(高考): 114

#   

#   尝试树深度=1 | 验证集(模拟考)得分: 0.9561

#   尝试树深度=5 | 验证集(模拟考)得分: 0.9474

#   尝试树深度=20 | 验证集(模拟考)得分: 0.9474

#   

#   模拟考结束！我们选定最佳超参数：max_depth = 1

#   模型最终的测试集(高考)真实成绩是: 0.9561




================================================
FILE: ML/ML_introduction/unsupervised_learning.ipynb
================================================
# Jupyter notebook converted to Python script.

"""
无监督学习(Unsupervised Learning)
定义：指在没有任何标签的数据集中寻找隐藏的结构、模式或者是规律。模型必须自己去发现数据中的内在特征，没有答案
"""

"""
无监督学习又分为两类：聚类(Clustering)和降维(Dimensionality Reduction)
聚类
定义：将数据分类，使得同族内的数据尽可能相似，不同组间的数据尽可能不同
降维
定义：在尽量不丢失重要信息的前提下，减少数据的特征数量，用于数据压缩和可视化
"""



================================================
FILE: ML/ML_projects/titanic/gender_submission.csv
================================================
PassengerId,Survived
892,0
893,1
894,0
895,0
896,1
897,0
898,1
899,0
900,1
901,0
902,0
903,0
904,1
905,0
906,1
907,1
908,0
909,0
910,1
911,1
912,0
913,0
914,1
915,0
916,1
917,0
918,1
919,0
920,0
921,0
922,0
923,0
924,1
925,1
926,0
927,0
928,1
929,1
930,0
931,0
932,0
933,0
934,0
935,1
936,1
937,0
938,0
939,0
940,1
941,1
942,0
943,0
944,1
945,1
946,0
947,0
948,0
949,0
950,0
951,1
952,0
953,0
954,0
955,1
956,0
957,1
958,1
959,0
960,0
961,1
962,1
963,0
964,1
965,0
966,1
967,0
968,0
969,1
970,0
971,1
972,0
973,0
974,0
975,0
976,0
977,0
978,1
979,1
980,1
981,0
982,1
983,0
984,1
985,0
986,0
987,0
988,1
989,0
990,1
991,0
992,1
993,0
994,0
995,0
996,1
997,0
998,0
999,0
1000,0
1001,0
1002,0
1003,1
1004,1
1005,1
1006,1
1007,0
1008,0
1009,1
1010,0
1011,1
1012,1
1013,0
1014,1
1015,0
1016,0
1017,1
1018,0
1019,1
1020,0
1021,0
1022,0
1023,0
1024,1
1025,0
1026,0
1027,0
1028,0
1029,0
1030,1
1031,0
1032,1
1033,1
1034,0
1035,0
1036,0
1037,0
1038,0
1039,0
1040,0
1041,0
1042,1
1043,0
1044,0
1045,1
1046,0
1047,0
1048,1
1049,1
1050,0
1051,1
1052,1
1053,0
1054,1
1055,0
1056,0
1057,1
1058,0
1059,0
1060,1
1061,1
1062,0
1063,0
1064,0
1065,0
1066,0
1067,1
1068,1
1069,0
1070,1
1071,1
1072,0
1073,0
1074,1
1075,0
1076,1
1077,0
1078,1
1079,0
1080,1
1081,0
1082,0
1083,0
1084,0
1085,0
1086,0
1087,0
1088,0
1089,1
1090,0
1091,1
1092,1
1093,0
1094,0
1095,1
1096,0
1097,0
1098,1
1099,0
1100,1
1101,0
1102,0
1103,0
1104,0
1105,1
1106,1
1107,0
1108,1
1109,0
1110,1
1111,0
1112,1
1113,0
1114,1
1115,0
1116,1
1117,1
1118,0
1119,1
1120,0
1121,0
1122,0
1123,1
1124,0
1125,0
1126,0
1127,0
1128,0
1129,0
1130,1
1131,1
1132,1
1133,1
1134,0
1135,0
1136,0
1137,0
1138,1
1139,0
1140,1
1141,1
1142,1
1143,0
1144,0
1145,0
1146,0
1147,0
1148,0
1149,0
1150,1
1151,0
1152,0
1153,0
1154,1
1155,1
1156,0
1157,0
1158,0
1159,0
1160,1
1161,0
1162,0
1163,0
1164,1
1165,1
1166,0
1167,1
1168,0
1169,0
1170,0
1171,0
1172,1
1173,0
1174,1
1175,1
1176,1
1177,0
1178,0
1179,0
1180,0
1181,0
1182,0
1183,1
1184,0
1185,0
1186,0
1187,0
1188,1
1189,0
1190,0
1191,0
1192,0
1193,0
1194,0
1195,0
1196,1
1197,1
1198,0
1199,0
1200,0
1201,1
1202,0
1203,0
1204,0
1205,1
1206,1
1207,1
1208,0
1209,0
1210,0
1211,0
1212,0
1213,0
1214,0
1215,0
1216,1
1217,0
1218,1
1219,0
1220,0
1221,0
1222,1
1223,0
1224,0
1225,1
1226,0
1227,0
1228,0
1229,0
1230,0
1231,0
1232,0
1233,0
1234,0
1235,1
1236,0
1237,1
1238,0
1239,1
1240,0
1241,1
1242,1
1243,0
1244,0
1245,0
1246,1
1247,0
1248,1
1249,0
1250,0
1251,1
1252,0
1253,1
1254,1
1255,0
1256,1
1257,1
1258,0
1259,1
1260,1
1261,0
1262,0
1263,1
1264,0
1265,0
1266,1
1267,1
1268,1
1269,0
1270,0
1271,0
1272,0
1273,0
1274,1
1275,1
1276,0
1277,1
1278,0
1279,0
1280,0
1281,0
1282,0
1283,1
1284,0
1285,0
1286,0
1287,1
1288,0
1289,1
1290,0
1291,0
1292,1
1293,0
1294,1
1295,0
1296,0
1297,0
1298,0
1299,0
1300,1
1301,1
1302,1
1303,1
1304,1
1305,0
1306,1
1307,0
1308,0
1309,0



================================================
FILE: ML/ML_projects/titanic/test.csv
================================================
PassengerId,Pclass,Name,Sex,Age,SibSp,Parch,Ticket,Fare,Cabin,Embarked
892,3,"Kelly, Mr. James",male,34.5,0,0,330911,7.8292,,Q
893,3,"Wilkes, Mrs. James (Ellen Needs)",female,47,1,0,363272,7,,S
894,2,"Myles, Mr. Thomas Francis",male,62,0,0,240276,9.6875,,Q
895,3,"Wirz, Mr. Albert",male,27,0,0,315154,8.6625,,S
896,3,"Hirvonen, Mrs. Alexander (Helga E Lindqvist)",female,22,1,1,3101298,12.2875,,S
897,3,"Svensson, Mr. Johan Cervin",male,14,0,0,7538,9.225,,S
898,3,"Connolly, Miss. Kate",female,30,0,0,330972,7.6292,,Q
899,2,"Caldwell, Mr. Albert Francis",male,26,1,1,248738,29,,S
900,3,"Abrahim, Mrs. Joseph (Sophie Halaut Easu)",female,18,0,0,2657,7.2292,,C
901,3,"Davies, Mr. John Samuel",male,21,2,0,A/4 48871,24.15,,S
902,3,"Ilieff, Mr. Ylio",male,,0,0,349220,7.8958,,S
903,1,"Jones, Mr. Charles Cresson",male,46,0,0,694,26,,S
904,1,"Snyder, Mrs. John Pillsbury (Nelle Stevenson)",female,23,1,0,21228,82.2667,B45,S
905,2,"Howard, Mr. Benjamin",male,63,1,0,24065,26,,S
906,1,"Chaffee, Mrs. Herbert Fuller (Carrie Constance Toogood)",female,47,1,0,W.E.P. 5734,61.175,E31,S
907,2,"del Carlo, Mrs. Sebastiano (Argenia Genovesi)",female,24,1,0,SC/PARIS 2167,27.7208,,C
908,2,"Keane, Mr. Daniel",male,35,0,0,233734,12.35,,Q
909,3,"Assaf, Mr. Gerios",male,21,0,0,2692,7.225,,C
910,3,"Ilmakangas, Miss. Ida Livija",female,27,1,0,STON/O2. 3101270,7.925,,S
911,3,"Assaf Khalil, Mrs. Mariana (Miriam"")""",female,45,0,0,2696,7.225,,C
912,1,"Rothschild, Mr. Martin",male,55,1,0,PC 17603,59.4,,C
913,3,"Olsen, Master. Artur Karl",male,9,0,1,C 17368,3.1708,,S
914,1,"Flegenheim, Mrs. Alfred (Antoinette)",female,,0,0,PC 17598,31.6833,,S
915,1,"Williams, Mr. Richard Norris II",male,21,0,1,PC 17597,61.3792,,C
916,1,"Ryerson, Mrs. Arthur Larned (Emily Maria Borie)",female,48,1,3,PC 17608,262.375,B57 B59 B63 B66,C
917,3,"Robins, Mr. Alexander A",male,50,1,0,A/5. 3337,14.5,,S
918,1,"Ostby, Miss. Helene Ragnhild",female,22,0,1,113509,61.9792,B36,C
919,3,"Daher, Mr. Shedid",male,22.5,0,0,2698,7.225,,C
920,1,"Brady, Mr. John Bertram",male,41,0,0,113054,30.5,A21,S
921,3,"Samaan, Mr. Elias",male,,2,0,2662,21.6792,,C
922,2,"Louch, Mr. Charles Alexander",male,50,1,0,SC/AH 3085,26,,S
923,2,"Jefferys, Mr. Clifford Thomas",male,24,2,0,C.A. 31029,31.5,,S
924,3,"Dean, Mrs. Bertram (Eva Georgetta Light)",female,33,1,2,C.A. 2315,20.575,,S
925,3,"Johnston, Mrs. Andrew G (Elizabeth Lily"" Watson)""",female,,1,2,W./C. 6607,23.45,,S
926,1,"Mock, Mr. Philipp Edmund",male,30,1,0,13236,57.75,C78,C
927,3,"Katavelas, Mr. Vassilios (Catavelas Vassilios"")""",male,18.5,0,0,2682,7.2292,,C
928,3,"Roth, Miss. Sarah A",female,,0,0,342712,8.05,,S
929,3,"Cacic, Miss. Manda",female,21,0,0,315087,8.6625,,S
930,3,"Sap, Mr. Julius",male,25,0,0,345768,9.5,,S
931,3,"Hee, Mr. Ling",male,,0,0,1601,56.4958,,S
932,3,"Karun, Mr. Franz",male,39,0,1,349256,13.4167,,C
933,1,"Franklin, Mr. Thomas Parham",male,,0,0,113778,26.55,D34,S
934,3,"Goldsmith, Mr. Nathan",male,41,0,0,SOTON/O.Q. 3101263,7.85,,S
935,2,"Corbett, Mrs. Walter H (Irene Colvin)",female,30,0,0,237249,13,,S
936,1,"Kimball, Mrs. Edwin Nelson Jr (Gertrude Parsons)",female,45,1,0,11753,52.5542,D19,S
937,3,"Peltomaki, Mr. Nikolai Johannes",male,25,0,0,STON/O 2. 3101291,7.925,,S
938,1,"Chevre, Mr. Paul Romaine",male,45,0,0,PC 17594,29.7,A9,C
939,3,"Shaughnessy, Mr. Patrick",male,,0,0,370374,7.75,,Q
940,1,"Bucknell, Mrs. William Robert (Emma Eliza Ward)",female,60,0,0,11813,76.2917,D15,C
941,3,"Coutts, Mrs. William (Winnie Minnie"" Treanor)""",female,36,0,2,C.A. 37671,15.9,,S
942,1,"Smith, Mr. Lucien Philip",male,24,1,0,13695,60,C31,S
943,2,"Pulbaum, Mr. Franz",male,27,0,0,SC/PARIS 2168,15.0333,,C
944,2,"Hocking, Miss. Ellen Nellie""""",female,20,2,1,29105,23,,S
945,1,"Fortune, Miss. Ethel Flora",female,28,3,2,19950,263,C23 C25 C27,S
946,2,"Mangiavacchi, Mr. Serafino Emilio",male,,0,0,SC/A.3 2861,15.5792,,C
947,3,"Rice, Master. Albert",male,10,4,1,382652,29.125,,Q
948,3,"Cor, Mr. Bartol",male,35,0,0,349230,7.8958,,S
949,3,"Abelseth, Mr. Olaus Jorgensen",male,25,0,0,348122,7.65,F G63,S
950,3,"Davison, Mr. Thomas Henry",male,,1,0,386525,16.1,,S
951,1,"Chaudanson, Miss. Victorine",female,36,0,0,PC 17608,262.375,B61,C
952,3,"Dika, Mr. Mirko",male,17,0,0,349232,7.8958,,S
953,2,"McCrae, Mr. Arthur Gordon",male,32,0,0,237216,13.5,,S
954,3,"Bjorklund, Mr. Ernst Herbert",male,18,0,0,347090,7.75,,S
955,3,"Bradley, Miss. Bridget Delia",female,22,0,0,334914,7.725,,Q
956,1,"Ryerson, Master. John Borie",male,13,2,2,PC 17608,262.375,B57 B59 B63 B66,C
957,2,"Corey, Mrs. Percy C (Mary Phyllis Elizabeth Miller)",female,,0,0,F.C.C. 13534,21,,S
958,3,"Burns, Miss. Mary Delia",female,18,0,0,330963,7.8792,,Q
959,1,"Moore, Mr. Clarence Bloomfield",male,47,0,0,113796,42.4,,S
960,1,"Tucker, Mr. Gilbert Milligan Jr",male,31,0,0,2543,28.5375,C53,C
961,1,"Fortune, Mrs. Mark (Mary McDougald)",female,60,1,4,19950,263,C23 C25 C27,S
962,3,"Mulvihill, Miss. Bertha E",female,24,0,0,382653,7.75,,Q
963,3,"Minkoff, Mr. Lazar",male,21,0,0,349211,7.8958,,S
964,3,"Nieminen, Miss. Manta Josefina",female,29,0,0,3101297,7.925,,S
965,1,"Ovies y Rodriguez, Mr. Servando",male,28.5,0,0,PC 17562,27.7208,D43,C
966,1,"Geiger, Miss. Amalie",female,35,0,0,113503,211.5,C130,C
967,1,"Keeping, Mr. Edwin",male,32.5,0,0,113503,211.5,C132,C
968,3,"Miles, Mr. Frank",male,,0,0,359306,8.05,,S
969,1,"Cornell, Mrs. Robert Clifford (Malvina Helen Lamson)",female,55,2,0,11770,25.7,C101,S
970,2,"Aldworth, Mr. Charles Augustus",male,30,0,0,248744,13,,S
971,3,"Doyle, Miss. Elizabeth",female,24,0,0,368702,7.75,,Q
972,3,"Boulos, Master. Akar",male,6,1,1,2678,15.2458,,C
973,1,"Straus, Mr. Isidor",male,67,1,0,PC 17483,221.7792,C55 C57,S
974,1,"Case, Mr. Howard Brown",male,49,0,0,19924,26,,S
975,3,"Demetri, Mr. Marinko",male,,0,0,349238,7.8958,,S
976,2,"Lamb, Mr. John Joseph",male,,0,0,240261,10.7083,,Q
977,3,"Khalil, Mr. Betros",male,,1,0,2660,14.4542,,C
978,3,"Barry, Miss. Julia",female,27,0,0,330844,7.8792,,Q
979,3,"Badman, Miss. Emily Louisa",female,18,0,0,A/4 31416,8.05,,S
980,3,"O'Donoghue, Ms. Bridget",female,,0,0,364856,7.75,,Q
981,2,"Wells, Master. Ralph Lester",male,2,1,1,29103,23,,S
982,3,"Dyker, Mrs. Adolf Fredrik (Anna Elisabeth Judith Andersson)",female,22,1,0,347072,13.9,,S
983,3,"Pedersen, Mr. Olaf",male,,0,0,345498,7.775,,S
984,1,"Davidson, Mrs. Thornton (Orian Hays)",female,27,1,2,F.C. 12750,52,B71,S
985,3,"Guest, Mr. Robert",male,,0,0,376563,8.05,,S
986,1,"Birnbaum, Mr. Jakob",male,25,0,0,13905,26,,C
987,3,"Tenglin, Mr. Gunnar Isidor",male,25,0,0,350033,7.7958,,S
988,1,"Cavendish, Mrs. Tyrell William (Julia Florence Siegel)",female,76,1,0,19877,78.85,C46,S
989,3,"Makinen, Mr. Kalle Edvard",male,29,0,0,STON/O 2. 3101268,7.925,,S
990,3,"Braf, Miss. Elin Ester Maria",female,20,0,0,347471,7.8542,,S
991,3,"Nancarrow, Mr. William Henry",male,33,0,0,A./5. 3338,8.05,,S
992,1,"Stengel, Mrs. Charles Emil Henry (Annie May Morris)",female,43,1,0,11778,55.4417,C116,C
993,2,"Weisz, Mr. Leopold",male,27,1,0,228414,26,,S
994,3,"Foley, Mr. William",male,,0,0,365235,7.75,,Q
995,3,"Johansson Palmquist, Mr. Oskar Leander",male,26,0,0,347070,7.775,,S
996,3,"Thomas, Mrs. Alexander (Thamine Thelma"")""",female,16,1,1,2625,8.5167,,C
997,3,"Holthen, Mr. Johan Martin",male,28,0,0,C 4001,22.525,,S
998,3,"Buckley, Mr. Daniel",male,21,0,0,330920,7.8208,,Q
999,3,"Ryan, Mr. Edward",male,,0,0,383162,7.75,,Q
1000,3,"Willer, Mr. Aaron (Abi Weller"")""",male,,0,0,3410,8.7125,,S
1001,2,"Swane, Mr. George",male,18.5,0,0,248734,13,F,S
1002,2,"Stanton, Mr. Samuel Ward",male,41,0,0,237734,15.0458,,C
1003,3,"Shine, Miss. Ellen Natalia",female,,0,0,330968,7.7792,,Q
1004,1,"Evans, Miss. Edith Corse",female,36,0,0,PC 17531,31.6792,A29,C
1005,3,"Buckley, Miss. Katherine",female,18.5,0,0,329944,7.2833,,Q
1006,1,"Straus, Mrs. Isidor (Rosalie Ida Blun)",female,63,1,0,PC 17483,221.7792,C55 C57,S
1007,3,"Chronopoulos, Mr. Demetrios",male,18,1,0,2680,14.4542,,C
1008,3,"Thomas, Mr. John",male,,0,0,2681,6.4375,,C
1009,3,"Sandstrom, Miss. Beatrice Irene",female,1,1,1,PP 9549,16.7,G6,S
1010,1,"Beattie, Mr. Thomson",male,36,0,0,13050,75.2417,C6,C
1011,2,"Chapman, Mrs. John Henry (Sara Elizabeth Lawry)",female,29,1,0,SC/AH 29037,26,,S
1012,2,"Watt, Miss. Bertha J",female,12,0,0,C.A. 33595,15.75,,S
1013,3,"Kiernan, Mr. John",male,,1,0,367227,7.75,,Q
1014,1,"Schabert, Mrs. Paul (Emma Mock)",female,35,1,0,13236,57.75,C28,C
1015,3,"Carver, Mr. Alfred John",male,28,0,0,392095,7.25,,S
1016,3,"Kennedy, Mr. John",male,,0,0,368783,7.75,,Q
1017,3,"Cribb, Miss. Laura Alice",female,17,0,1,371362,16.1,,S
1018,3,"Brobeck, Mr. Karl Rudolf",male,22,0,0,350045,7.7958,,S
1019,3,"McCoy, Miss. Alicia",female,,2,0,367226,23.25,,Q
1020,2,"Bowenur, Mr. Solomon",male,42,0,0,211535,13,,S
1021,3,"Petersen, Mr. Marius",male,24,0,0,342441,8.05,,S
1022,3,"Spinner, Mr. Henry John",male,32,0,0,STON/OQ. 369943,8.05,,S
1023,1,"Gracie, Col. Archibald IV",male,53,0,0,113780,28.5,C51,C
1024,3,"Lefebre, Mrs. Frank (Frances)",female,,0,4,4133,25.4667,,S
1025,3,"Thomas, Mr. Charles P",male,,1,0,2621,6.4375,,C
1026,3,"Dintcheff, Mr. Valtcho",male,43,0,0,349226,7.8958,,S
1027,3,"Carlsson, Mr. Carl Robert",male,24,0,0,350409,7.8542,,S
1028,3,"Zakarian, Mr. Mapriededer",male,26.5,0,0,2656,7.225,,C
1029,2,"Schmidt, Mr. August",male,26,0,0,248659,13,,S
1030,3,"Drapkin, Miss. Jennie",female,23,0,0,SOTON/OQ 392083,8.05,,S
1031,3,"Goodwin, Mr. Charles Frederick",male,40,1,6,CA 2144,46.9,,S
1032,3,"Goodwin, Miss. Jessie Allis",female,10,5,2,CA 2144,46.9,,S
1033,1,"Daniels, Miss. Sarah",female,33,0,0,113781,151.55,,S
1034,1,"Ryerson, Mr. Arthur Larned",male,61,1,3,PC 17608,262.375,B57 B59 B63 B66,C
1035,2,"Beauchamp, Mr. Henry James",male,28,0,0,244358,26,,S
1036,1,"Lindeberg-Lind, Mr. Erik Gustaf (Mr Edward Lingrey"")""",male,42,0,0,17475,26.55,,S
1037,3,"Vander Planke, Mr. Julius",male,31,3,0,345763,18,,S
1038,1,"Hilliard, Mr. Herbert Henry",male,,0,0,17463,51.8625,E46,S
1039,3,"Davies, Mr. Evan",male,22,0,0,SC/A4 23568,8.05,,S
1040,1,"Crafton, Mr. John Bertram",male,,0,0,113791,26.55,,S
1041,2,"Lahtinen, Rev. William",male,30,1,1,250651,26,,S
1042,1,"Earnshaw, Mrs. Boulton (Olive Potter)",female,23,0,1,11767,83.1583,C54,C
1043,3,"Matinoff, Mr. Nicola",male,,0,0,349255,7.8958,,C
1044,3,"Storey, Mr. Thomas",male,60.5,0,0,3701,,,S
1045,3,"Klasen, Mrs. (Hulda Kristina Eugenia Lofqvist)",female,36,0,2,350405,12.1833,,S
1046,3,"Asplund, Master. Filip Oscar",male,13,4,2,347077,31.3875,,S
1047,3,"Duquemin, Mr. Joseph",male,24,0,0,S.O./P.P. 752,7.55,,S
1048,1,"Bird, Miss. Ellen",female,29,0,0,PC 17483,221.7792,C97,S
1049,3,"Lundin, Miss. Olga Elida",female,23,0,0,347469,7.8542,,S
1050,1,"Borebank, Mr. John James",male,42,0,0,110489,26.55,D22,S
1051,3,"Peacock, Mrs. Benjamin (Edith Nile)",female,26,0,2,SOTON/O.Q. 3101315,13.775,,S
1052,3,"Smyth, Miss. Julia",female,,0,0,335432,7.7333,,Q
1053,3,"Touma, Master. Georges Youssef",male,7,1,1,2650,15.2458,,C
1054,2,"Wright, Miss. Marion",female,26,0,0,220844,13.5,,S
1055,3,"Pearce, Mr. Ernest",male,,0,0,343271,7,,S
1056,2,"Peruschitz, Rev. Joseph Maria",male,41,0,0,237393,13,,S
1057,3,"Kink-Heilmann, Mrs. Anton (Luise Heilmann)",female,26,1,1,315153,22.025,,S
1058,1,"Brandeis, Mr. Emil",male,48,0,0,PC 17591,50.4958,B10,C
1059,3,"Ford, Mr. Edward Watson",male,18,2,2,W./C. 6608,34.375,,S
1060,1,"Cassebeer, Mrs. Henry Arthur Jr (Eleanor Genevieve Fosdick)",female,,0,0,17770,27.7208,,C
1061,3,"Hellstrom, Miss. Hilda Maria",female,22,0,0,7548,8.9625,,S
1062,3,"Lithman, Mr. Simon",male,,0,0,S.O./P.P. 251,7.55,,S
1063,3,"Zakarian, Mr. Ortin",male,27,0,0,2670,7.225,,C
1064,3,"Dyker, Mr. Adolf Fredrik",male,23,1,0,347072,13.9,,S
1065,3,"Torfa, Mr. Assad",male,,0,0,2673,7.2292,,C
1066,3,"Asplund, Mr. Carl Oscar Vilhelm Gustafsson",male,40,1,5,347077,31.3875,,S
1067,2,"Brown, Miss. Edith Eileen",female,15,0,2,29750,39,,S
1068,2,"Sincock, Miss. Maude",female,20,0,0,C.A. 33112,36.75,,S
1069,1,"Stengel, Mr. Charles Emil Henry",male,54,1,0,11778,55.4417,C116,C
1070,2,"Becker, Mrs. Allen Oliver (Nellie E Baumgardner)",female,36,0,3,230136,39,F4,S
1071,1,"Compton, Mrs. Alexander Taylor (Mary Eliza Ingersoll)",female,64,0,2,PC 17756,83.1583,E45,C
1072,2,"McCrie, Mr. James Matthew",male,30,0,0,233478,13,,S
1073,1,"Compton, Mr. Alexander Taylor Jr",male,37,1,1,PC 17756,83.1583,E52,C
1074,1,"Marvin, Mrs. Daniel Warner (Mary Graham Carmichael Farquarson)",female,18,1,0,113773,53.1,D30,S
1075,3,"Lane, Mr. Patrick",male,,0,0,7935,7.75,,Q
1076,1,"Douglas, Mrs. Frederick Charles (Mary Helene Baxter)",female,27,1,1,PC 17558,247.5208,B58 B60,C
1077,2,"Maybery, Mr. Frank Hubert",male,40,0,0,239059,16,,S
1078,2,"Phillips, Miss. Alice Frances Louisa",female,21,0,1,S.O./P.P. 2,21,,S
1079,3,"Davies, Mr. Joseph",male,17,2,0,A/4 48873,8.05,,S
1080,3,"Sage, Miss. Ada",female,,8,2,CA. 2343,69.55,,S
1081,2,"Veal, Mr. James",male,40,0,0,28221,13,,S
1082,2,"Angle, Mr. William A",male,34,1,0,226875,26,,S
1083,1,"Salomon, Mr. Abraham L",male,,0,0,111163,26,,S
1084,3,"van Billiard, Master. Walter John",male,11.5,1,1,A/5. 851,14.5,,S
1085,2,"Lingane, Mr. John",male,61,0,0,235509,12.35,,Q
1086,2,"Drew, Master. Marshall Brines",male,8,0,2,28220,32.5,,S
1087,3,"Karlsson, Mr. Julius Konrad Eugen",male,33,0,0,347465,7.8542,,S
1088,1,"Spedden, Master. Robert Douglas",male,6,0,2,16966,134.5,E34,C
1089,3,"Nilsson, Miss. Berta Olivia",female,18,0,0,347066,7.775,,S
1090,2,"Baimbrigge, Mr. Charles Robert",male,23,0,0,C.A. 31030,10.5,,S
1091,3,"Rasmussen, Mrs. (Lena Jacobsen Solvang)",female,,0,0,65305,8.1125,,S
1092,3,"Murphy, Miss. Nora",female,,0,0,36568,15.5,,Q
1093,3,"Danbom, Master. Gilbert Sigvard Emanuel",male,0.33,0,2,347080,14.4,,S
1094,1,"Astor, Col. John Jacob",male,47,1,0,PC 17757,227.525,C62 C64,C
1095,2,"Quick, Miss. Winifred Vera",female,8,1,1,26360,26,,S
1096,2,"Andrew, Mr. Frank Thomas",male,25,0,0,C.A. 34050,10.5,,S
1097,1,"Omont, Mr. Alfred Fernand",male,,0,0,F.C. 12998,25.7417,,C
1098,3,"McGowan, Miss. Katherine",female,35,0,0,9232,7.75,,Q
1099,2,"Collett, Mr. Sidney C Stuart",male,24,0,0,28034,10.5,,S
1100,1,"Rosenbaum, Miss. Edith Louise",female,33,0,0,PC 17613,27.7208,A11,C
1101,3,"Delalic, Mr. Redjo",male,25,0,0,349250,7.8958,,S
1102,3,"Andersen, Mr. Albert Karvin",male,32,0,0,C 4001,22.525,,S
1103,3,"Finoli, Mr. Luigi",male,,0,0,SOTON/O.Q. 3101308,7.05,,S
1104,2,"Deacon, Mr. Percy William",male,17,0,0,S.O.C. 14879,73.5,,S
1105,2,"Howard, Mrs. Benjamin (Ellen Truelove Arman)",female,60,1,0,24065,26,,S
1106,3,"Andersson, Miss. Ida Augusta Margareta",female,38,4,2,347091,7.775,,S
1107,1,"Head, Mr. Christopher",male,42,0,0,113038,42.5,B11,S
1108,3,"Mahon, Miss. Bridget Delia",female,,0,0,330924,7.8792,,Q
1109,1,"Wick, Mr. George Dennick",male,57,1,1,36928,164.8667,,S
1110,1,"Widener, Mrs. George Dunton (Eleanor Elkins)",female,50,1,1,113503,211.5,C80,C
1111,3,"Thomson, Mr. Alexander Morrison",male,,0,0,32302,8.05,,S
1112,2,"Duran y More, Miss. Florentina",female,30,1,0,SC/PARIS 2148,13.8583,,C
1113,3,"Reynolds, Mr. Harold J",male,21,0,0,342684,8.05,,S
1114,2,"Cook, Mrs. (Selena Rogers)",female,22,0,0,W./C. 14266,10.5,F33,S
1115,3,"Karlsson, Mr. Einar Gervasius",male,21,0,0,350053,7.7958,,S
1116,1,"Candee, Mrs. Edward (Helen Churchill Hungerford)",female,53,0,0,PC 17606,27.4458,,C
1117,3,"Moubarek, Mrs. George (Omine Amenia"" Alexander)""",female,,0,2,2661,15.2458,,C
1118,3,"Asplund, Mr. Johan Charles",male,23,0,0,350054,7.7958,,S
1119,3,"McNeill, Miss. Bridget",female,,0,0,370368,7.75,,Q
1120,3,"Everett, Mr. Thomas James",male,40.5,0,0,C.A. 6212,15.1,,S
1121,2,"Hocking, Mr. Samuel James Metcalfe",male,36,0,0,242963,13,,S
1122,2,"Sweet, Mr. George Frederick",male,14,0,0,220845,65,,S
1123,1,"Willard, Miss. Constance",female,21,0,0,113795,26.55,,S
1124,3,"Wiklund, Mr. Karl Johan",male,21,1,0,3101266,6.4958,,S
1125,3,"Linehan, Mr. Michael",male,,0,0,330971,7.8792,,Q
1126,1,"Cumings, Mr. John Bradley",male,39,1,0,PC 17599,71.2833,C85,C
1127,3,"Vendel, Mr. Olof Edvin",male,20,0,0,350416,7.8542,,S
1128,1,"Warren, Mr. Frank Manley",male,64,1,0,110813,75.25,D37,C
1129,3,"Baccos, Mr. Raffull",male,20,0,0,2679,7.225,,C
1130,2,"Hiltunen, Miss. Marta",female,18,1,1,250650,13,,S
1131,1,"Douglas, Mrs. Walter Donald (Mahala Dutton)",female,48,1,0,PC 17761,106.425,C86,C
1132,1,"Lindstrom, Mrs. Carl Johan (Sigrid Posse)",female,55,0,0,112377,27.7208,,C
1133,2,"Christy, Mrs. (Alice Frances)",female,45,0,2,237789,30,,S
1134,1,"Spedden, Mr. Frederic Oakley",male,45,1,1,16966,134.5,E34,C
1135,3,"Hyman, Mr. Abraham",male,,0,0,3470,7.8875,,S
1136,3,"Johnston, Master. William Arthur Willie""""",male,,1,2,W./C. 6607,23.45,,S
1137,1,"Kenyon, Mr. Frederick R",male,41,1,0,17464,51.8625,D21,S
1138,2,"Karnes, Mrs. J Frank (Claire Bennett)",female,22,0,0,F.C.C. 13534,21,,S
1139,2,"Drew, Mr. James Vivian",male,42,1,1,28220,32.5,,S
1140,2,"Hold, Mrs. Stephen (Annie Margaret Hill)",female,29,1,0,26707,26,,S
1141,3,"Khalil, Mrs. Betros (Zahie Maria"" Elias)""",female,,1,0,2660,14.4542,,C
1142,2,"West, Miss. Barbara J",female,0.92,1,2,C.A. 34651,27.75,,S
1143,3,"Abrahamsson, Mr. Abraham August Johannes",male,20,0,0,SOTON/O2 3101284,7.925,,S
1144,1,"Clark, Mr. Walter Miller",male,27,1,0,13508,136.7792,C89,C
1145,3,"Salander, Mr. Karl Johan",male,24,0,0,7266,9.325,,S
1146,3,"Wenzel, Mr. Linhart",male,32.5,0,0,345775,9.5,,S
1147,3,"MacKay, Mr. George William",male,,0,0,C.A. 42795,7.55,,S
1148,3,"Mahon, Mr. John",male,,0,0,AQ/4 3130,7.75,,Q
1149,3,"Niklasson, Mr. Samuel",male,28,0,0,363611,8.05,,S
1150,2,"Bentham, Miss. Lilian W",female,19,0,0,28404,13,,S
1151,3,"Midtsjo, Mr. Karl Albert",male,21,0,0,345501,7.775,,S
1152,3,"de Messemaeker, Mr. Guillaume Joseph",male,36.5,1,0,345572,17.4,,S
1153,3,"Nilsson, Mr. August Ferdinand",male,21,0,0,350410,7.8542,,S
1154,2,"Wells, Mrs. Arthur Henry (Addie"" Dart Trevaskis)""",female,29,0,2,29103,23,,S
1155,3,"Klasen, Miss. Gertrud Emilia",female,1,1,1,350405,12.1833,,S
1156,2,"Portaluppi, Mr. Emilio Ilario Giuseppe",male,30,0,0,C.A. 34644,12.7375,,C
1157,3,"Lyntakoff, Mr. Stanko",male,,0,0,349235,7.8958,,S
1158,1,"Chisholm, Mr. Roderick Robert Crispin",male,,0,0,112051,0,,S
1159,3,"Warren, Mr. Charles William",male,,0,0,C.A. 49867,7.55,,S
1160,3,"Howard, Miss. May Elizabeth",female,,0,0,A. 2. 39186,8.05,,S
1161,3,"Pokrnic, Mr. Mate",male,17,0,0,315095,8.6625,,S
1162,1,"McCaffry, Mr. Thomas Francis",male,46,0,0,13050,75.2417,C6,C
1163,3,"Fox, Mr. Patrick",male,,0,0,368573,7.75,,Q
1164,1,"Clark, Mrs. Walter Miller (Virginia McDowell)",female,26,1,0,13508,136.7792,C89,C
1165,3,"Lennon, Miss. Mary",female,,1,0,370371,15.5,,Q
1166,3,"Saade, Mr. Jean Nassr",male,,0,0,2676,7.225,,C
1167,2,"Bryhl, Miss. Dagmar Jenny Ingeborg ",female,20,1,0,236853,26,,S
1168,2,"Parker, Mr. Clifford Richard",male,28,0,0,SC 14888,10.5,,S
1169,2,"Faunthorpe, Mr. Harry",male,40,1,0,2926,26,,S
1170,2,"Ware, Mr. John James",male,30,1,0,CA 31352,21,,S
1171,2,"Oxenham, Mr. Percy Thomas",male,22,0,0,W./C. 14260,10.5,,S
1172,3,"Oreskovic, Miss. Jelka",female,23,0,0,315085,8.6625,,S
1173,3,"Peacock, Master. Alfred Edward",male,0.75,1,1,SOTON/O.Q. 3101315,13.775,,S
1174,3,"Fleming, Miss. Honora",female,,0,0,364859,7.75,,Q
1175,3,"Touma, Miss. Maria Youssef",female,9,1,1,2650,15.2458,,C
1176,3,"Rosblom, Miss. Salli Helena",female,2,1,1,370129,20.2125,,S
1177,3,"Dennis, Mr. William",male,36,0,0,A/5 21175,7.25,,S
1178,3,"Franklin, Mr. Charles (Charles Fardon)",male,,0,0,SOTON/O.Q. 3101314,7.25,,S
1179,1,"Snyder, Mr. John Pillsbury",male,24,1,0,21228,82.2667,B45,S
1180,3,"Mardirosian, Mr. Sarkis",male,,0,0,2655,7.2292,F E46,C
1181,3,"Ford, Mr. Arthur",male,,0,0,A/5 1478,8.05,,S
1182,1,"Rheims, Mr. George Alexander Lucien",male,,0,0,PC 17607,39.6,,S
1183,3,"Daly, Miss. Margaret Marcella Maggie""""",female,30,0,0,382650,6.95,,Q
1184,3,"Nasr, Mr. Mustafa",male,,0,0,2652,7.2292,,C
1185,1,"Dodge, Dr. Washington",male,53,1,1,33638,81.8583,A34,S
1186,3,"Wittevrongel, Mr. Camille",male,36,0,0,345771,9.5,,S
1187,3,"Angheloff, Mr. Minko",male,26,0,0,349202,7.8958,,S
1188,2,"Laroche, Miss. Louise",female,1,1,2,SC/Paris 2123,41.5792,,C
1189,3,"Samaan, Mr. Hanna",male,,2,0,2662,21.6792,,C
1190,1,"Loring, Mr. Joseph Holland",male,30,0,0,113801,45.5,,S
1191,3,"Johansson, Mr. Nils",male,29,0,0,347467,7.8542,,S
1192,3,"Olsson, Mr. Oscar Wilhelm",male,32,0,0,347079,7.775,,S
1193,2,"Malachard, Mr. Noel",male,,0,0,237735,15.0458,D,C
1194,2,"Phillips, Mr. Escott Robert",male,43,0,1,S.O./P.P. 2,21,,S
1195,3,"Pokrnic, Mr. Tome",male,24,0,0,315092,8.6625,,S
1196,3,"McCarthy, Miss. Catherine Katie""""",female,,0,0,383123,7.75,,Q
1197,1,"Crosby, Mrs. Edward Gifford (Catherine Elizabeth Halstead)",female,64,1,1,112901,26.55,B26,S
1198,1,"Allison, Mr. Hudson Joshua Creighton",male,30,1,2,113781,151.55,C22 C26,S
1199,3,"Aks, Master. Philip Frank",male,0.83,0,1,392091,9.35,,S
1200,1,"Hays, Mr. Charles Melville",male,55,1,1,12749,93.5,B69,S
1201,3,"Hansen, Mrs. Claus Peter (Jennie L Howard)",female,45,1,0,350026,14.1083,,S
1202,3,"Cacic, Mr. Jego Grga",male,18,0,0,315091,8.6625,,S
1203,3,"Vartanian, Mr. David",male,22,0,0,2658,7.225,,C
1204,3,"Sadowitz, Mr. Harry",male,,0,0,LP 1588,7.575,,S
1205,3,"Carr, Miss. Jeannie",female,37,0,0,368364,7.75,,Q
1206,1,"White, Mrs. John Stuart (Ella Holmes)",female,55,0,0,PC 17760,135.6333,C32,C
1207,3,"Hagardon, Miss. Kate",female,17,0,0,AQ/3. 30631,7.7333,,Q
1208,1,"Spencer, Mr. William Augustus",male,57,1,0,PC 17569,146.5208,B78,C
1209,2,"Rogers, Mr. Reginald Harry",male,19,0,0,28004,10.5,,S
1210,3,"Jonsson, Mr. Nils Hilding",male,27,0,0,350408,7.8542,,S
1211,2,"Jefferys, Mr. Ernest Wilfred",male,22,2,0,C.A. 31029,31.5,,S
1212,3,"Andersson, Mr. Johan Samuel",male,26,0,0,347075,7.775,,S
1213,3,"Krekorian, Mr. Neshan",male,25,0,0,2654,7.2292,F E57,C
1214,2,"Nesson, Mr. Israel",male,26,0,0,244368,13,F2,S
1215,1,"Rowe, Mr. Alfred G",male,33,0,0,113790,26.55,,S
1216,1,"Kreuchen, Miss. Emilie",female,39,0,0,24160,211.3375,,S
1217,3,"Assam, Mr. Ali",male,23,0,0,SOTON/O.Q. 3101309,7.05,,S
1218,2,"Becker, Miss. Ruth Elizabeth",female,12,2,1,230136,39,F4,S
1219,1,"Rosenshine, Mr. George (Mr George Thorne"")""",male,46,0,0,PC 17585,79.2,,C
1220,2,"Clarke, Mr. Charles Valentine",male,29,1,0,2003,26,,S
1221,2,"Enander, Mr. Ingvar",male,21,0,0,236854,13,,S
1222,2,"Davies, Mrs. John Morgan (Elizabeth Agnes Mary White) ",female,48,0,2,C.A. 33112,36.75,,S
1223,1,"Dulles, Mr. William Crothers",male,39,0,0,PC 17580,29.7,A18,C
1224,3,"Thomas, Mr. Tannous",male,,0,0,2684,7.225,,C
1225,3,"Nakid, Mrs. Said (Waika Mary"" Mowad)""",female,19,1,1,2653,15.7417,,C
1226,3,"Cor, Mr. Ivan",male,27,0,0,349229,7.8958,,S
1227,1,"Maguire, Mr. John Edward",male,30,0,0,110469,26,C106,S
1228,2,"de Brito, Mr. Jose Joaquim",male,32,0,0,244360,13,,S
1229,3,"Elias, Mr. Joseph",male,39,0,2,2675,7.2292,,C
1230,2,"Denbury, Mr. Herbert",male,25,0,0,C.A. 31029,31.5,,S
1231,3,"Betros, Master. Seman",male,,0,0,2622,7.2292,,C
1232,2,"Fillbrook, Mr. Joseph Charles",male,18,0,0,C.A. 15185,10.5,,S
1233,3,"Lundstrom, Mr. Thure Edvin",male,32,0,0,350403,7.5792,,S
1234,3,"Sage, Mr. John George",male,,1,9,CA. 2343,69.55,,S
1235,1,"Cardeza, Mrs. James Warburton Martinez (Charlotte Wardle Drake)",female,58,0,1,PC 17755,512.3292,B51 B53 B55,C
1236,3,"van Billiard, Master. James William",male,,1,1,A/5. 851,14.5,,S
1237,3,"Abelseth, Miss. Karen Marie",female,16,0,0,348125,7.65,,S
1238,2,"Botsford, Mr. William Hull",male,26,0,0,237670,13,,S
1239,3,"Whabee, Mrs. George Joseph (Shawneene Abi-Saab)",female,38,0,0,2688,7.2292,,C
1240,2,"Giles, Mr. Ralph",male,24,0,0,248726,13.5,,S
1241,2,"Walcroft, Miss. Nellie",female,31,0,0,F.C.C. 13528,21,,S
1242,1,"Greenfield, Mrs. Leo David (Blanche Strouse)",female,45,0,1,PC 17759,63.3583,D10 D12,C
1243,2,"Stokes, Mr. Philip Joseph",male,25,0,0,F.C.C. 13540,10.5,,S
1244,2,"Dibden, Mr. William",male,18,0,0,S.O.C. 14879,73.5,,S
1245,2,"Herman, Mr. Samuel",male,49,1,2,220845,65,,S
1246,3,"Dean, Miss. Elizabeth Gladys Millvina""""",female,0.17,1,2,C.A. 2315,20.575,,S
1247,1,"Julian, Mr. Henry Forbes",male,50,0,0,113044,26,E60,S
1248,1,"Brown, Mrs. John Murray (Caroline Lane Lamson)",female,59,2,0,11769,51.4792,C101,S
1249,3,"Lockyer, Mr. Edward",male,,0,0,1222,7.8792,,S
1250,3,"O'Keefe, Mr. Patrick",male,,0,0,368402,7.75,,Q
1251,3,"Lindell, Mrs. Edvard Bengtsson (Elin Gerda Persson)",female,30,1,0,349910,15.55,,S
1252,3,"Sage, Master. William Henry",male,14.5,8,2,CA. 2343,69.55,,S
1253,2,"Mallet, Mrs. Albert (Antoinette Magnin)",female,24,1,1,S.C./PARIS 2079,37.0042,,C
1254,2,"Ware, Mrs. John James (Florence Louise Long)",female,31,0,0,CA 31352,21,,S
1255,3,"Strilic, Mr. Ivan",male,27,0,0,315083,8.6625,,S
1256,1,"Harder, Mrs. George Achilles (Dorothy Annan)",female,25,1,0,11765,55.4417,E50,C
1257,3,"Sage, Mrs. John (Annie Bullen)",female,,1,9,CA. 2343,69.55,,S
1258,3,"Caram, Mr. Joseph",male,,1,0,2689,14.4583,,C
1259,3,"Riihivouri, Miss. Susanna Juhantytar Sanni""""",female,22,0,0,3101295,39.6875,,S
1260,1,"Gibson, Mrs. Leonard (Pauline C Boeson)",female,45,0,1,112378,59.4,,C
1261,2,"Pallas y Castello, Mr. Emilio",male,29,0,0,SC/PARIS 2147,13.8583,,C
1262,2,"Giles, Mr. Edgar",male,21,1,0,28133,11.5,,S
1263,1,"Wilson, Miss. Helen Alice",female,31,0,0,16966,134.5,E39 E41,C
1264,1,"Ismay, Mr. Joseph Bruce",male,49,0,0,112058,0,B52 B54 B56,S
1265,2,"Harbeck, Mr. William H",male,44,0,0,248746,13,,S
1266,1,"Dodge, Mrs. Washington (Ruth Vidaver)",female,54,1,1,33638,81.8583,A34,S
1267,1,"Bowen, Miss. Grace Scott",female,45,0,0,PC 17608,262.375,,C
1268,3,"Kink, Miss. Maria",female,22,2,0,315152,8.6625,,S
1269,2,"Cotterill, Mr. Henry Harry""""",male,21,0,0,29107,11.5,,S
1270,1,"Hipkins, Mr. William Edward",male,55,0,0,680,50,C39,S
1271,3,"Asplund, Master. Carl Edgar",male,5,4,2,347077,31.3875,,S
1272,3,"O'Connor, Mr. Patrick",male,,0,0,366713,7.75,,Q
1273,3,"Foley, Mr. Joseph",male,26,0,0,330910,7.8792,,Q
1274,3,"Risien, Mrs. Samuel (Emma)",female,,0,0,364498,14.5,,S
1275,3,"McNamee, Mrs. Neal (Eileen O'Leary)",female,19,1,0,376566,16.1,,S
1276,2,"Wheeler, Mr. Edwin Frederick""""",male,,0,0,SC/PARIS 2159,12.875,,S
1277,2,"Herman, Miss. Kate",female,24,1,2,220845,65,,S
1278,3,"Aronsson, Mr. Ernst Axel Algot",male,24,0,0,349911,7.775,,S
1279,2,"Ashby, Mr. John",male,57,0,0,244346,13,,S
1280,3,"Canavan, Mr. Patrick",male,21,0,0,364858,7.75,,Q
1281,3,"Palsson, Master. Paul Folke",male,6,3,1,349909,21.075,,S
1282,1,"Payne, Mr. Vivian Ponsonby",male,23,0,0,12749,93.5,B24,S
1283,1,"Lines, Mrs. Ernest H (Elizabeth Lindsey James)",female,51,0,1,PC 17592,39.4,D28,S
1284,3,"Abbott, Master. Eugene Joseph",male,13,0,2,C.A. 2673,20.25,,S
1285,2,"Gilbert, Mr. William",male,47,0,0,C.A. 30769,10.5,,S
1286,3,"Kink-Heilmann, Mr. Anton",male,29,3,1,315153,22.025,,S
1287,1,"Smith, Mrs. Lucien Philip (Mary Eloise Hughes)",female,18,1,0,13695,60,C31,S
1288,3,"Colbert, Mr. Patrick",male,24,0,0,371109,7.25,,Q
1289,1,"Frolicher-Stehli, Mrs. Maxmillian (Margaretha Emerentia Stehli)",female,48,1,1,13567,79.2,B41,C
1290,3,"Larsson-Rondberg, Mr. Edvard A",male,22,0,0,347065,7.775,,S
1291,3,"Conlon, Mr. Thomas Henry",male,31,0,0,21332,7.7333,,Q
1292,1,"Bonnell, Miss. Caroline",female,30,0,0,36928,164.8667,C7,S
1293,2,"Gale, Mr. Harry",male,38,1,0,28664,21,,S
1294,1,"Gibson, Miss. Dorothy Winifred",female,22,0,1,112378,59.4,,C
1295,1,"Carrau, Mr. Jose Pedro",male,17,0,0,113059,47.1,,S
1296,1,"Frauenthal, Mr. Isaac Gerald",male,43,1,0,17765,27.7208,D40,C
1297,2,"Nourney, Mr. Alfred (Baron von Drachstedt"")""",male,20,0,0,SC/PARIS 2166,13.8625,D38,C
1298,2,"Ware, Mr. William Jeffery",male,23,1,0,28666,10.5,,S
1299,1,"Widener, Mr. George Dunton",male,50,1,1,113503,211.5,C80,C
1300,3,"Riordan, Miss. Johanna Hannah""""",female,,0,0,334915,7.7208,,Q
1301,3,"Peacock, Miss. Treasteall",female,3,1,1,SOTON/O.Q. 3101315,13.775,,S
1302,3,"Naughton, Miss. Hannah",female,,0,0,365237,7.75,,Q
1303,1,"Minahan, Mrs. William Edward (Lillian E Thorpe)",female,37,1,0,19928,90,C78,Q
1304,3,"Henriksson, Miss. Jenny Lovisa",female,28,0,0,347086,7.775,,S
1305,3,"Spector, Mr. Woolf",male,,0,0,A.5. 3236,8.05,,S
1306,1,"Oliva y Ocana, Dona. Fermina",female,39,0,0,PC 17758,108.9,C105,C
1307,3,"Saether, Mr. Simon Sivertsen",male,38.5,0,0,SOTON/O.Q. 3101262,7.25,,S
1308,3,"Ware, Mr. Frederick",male,,0,0,359309,8.05,,S
1309,3,"Peter, Master. Michael J",male,,1,1,2668,22.3583,,C



================================================
FILE: ML/ML_projects/titanic/titanic.ipynb
================================================
# Jupyter notebook converted to Python script.

import pandas as pd

df = pd.read_csv("train.csv")
print(df.head()) # 只看前五行
# Output:
#      PassengerId  Survived  Pclass  \

#   0            1         0       3   

#   1            2         1       1   

#   2            3         1       3   

#   3            4         1       1   

#   4            5         0       3   

#   

#                                                   Name     Sex   Age  SibSp  \

#   0                            Braund, Mr. Owen Harris    male  22.0      1   

#   1  Cumings, Mrs. John Bradley (Florence Briggs Th...  female  38.0      1   

#   2                             Heikkinen, Miss. Laina  female  26.0      0   

#   3       Futrelle, Mrs. Jacques Heath (Lily May Peel)  female  35.0      1   

#   4                           Allen, Mr. William Henry    male  35.0      0   

#   

#      Parch            Ticket     Fare Cabin Embarked  

#   0      0         A/5 21171   7.2500   NaN        S  

#   1      0          PC 17599  71.2833   C85        C  

#   2      0  STON/O2. 3101282   7.9250   NaN        S  

#   3      0            113803  53.1000  C123        S  

#   4      0            373450   8.0500   NaN        S  


"""
Survived：0 = 遇难，1 = 生还。
Pclass：客舱等级（1 = 头等舱，2 = 二等舱，3 = 三等舱。这代表了乘客的社会地位）。
Name：姓名。
Sex：性别。
Age：年龄。
SibSp：该乘客在船上的 兄弟姐妹/配偶 数量。
Parch：该乘客在船上的 父母/孩子 数量。
Ticket：船票号码。
Fare：买船票花的钱。
Cabin：客舱编号。
Embarked：登船的港口（C = 瑟堡，Q = 皇后镇，S = 南安普顿）。
"""

"""
年龄当中的缺失值我们选择用中位数来填，因为平均数很容易受极端数据的影响，导致数据不准确
"""

median_age = df["Age"].median()
df['Age'] = df["Age"].fillna(median_age)

"""
男性和女性我们分别用0和1代替
在泰坦尼克号那个“女士优先”的背景下，女性的生还率比男性更高，所以当机器计算权重w时，算出来的w大概率是一个很大的整数
"""

df['Sex'] = df['Sex'].map({'female': 1, 'male': 0})
print(df[['Name', 'Sex']].head())
# Output:
#                                                   Name  Sex

#   0                            Braund, Mr. Owen Harris    0

#   1  Cumings, Mrs. John Bradley (Florence Briggs Th...    1

#   2                             Heikkinen, Miss. Laina    1

#   3       Futrelle, Mrs. Jacques Heath (Lily May Peel)    1

#   4                           Allen, Mr. William Henry    0


"""
对于上岸港口，对生还率没有任何影响，所以我们把原数据转换为列表，列表元素等于上岸港口的个数，对应的港口，体现在对应列表中的位置对应元素为1
"""

df = pd.get_dummies(df, columns=['Embarked'])
print(df.head())
# Output:
#      PassengerId  Survived  Pclass  \

#   0            1         0       3   

#   1            2         1       1   

#   2            3         1       3   

#   3            4         1       1   

#   4            5         0       3   

#   

#                                                   Name  Sex   Age  SibSp  Parch  \

#   0                            Braund, Mr. Owen Harris    0  22.0      1      0   

#   1  Cumings, Mrs. John Bradley (Florence Briggs Th...    1  38.0      1      0   

#   2                             Heikkinen, Miss. Laina    1  26.0      0      0   

#   3       Futrelle, Mrs. Jacques Heath (Lily May Peel)    1  35.0      1      0   

#   4                           Allen, Mr. William Henry    0  35.0      0      0   

#   

#                Ticket     Fare Cabin  Embarked_C  Embarked_Q  Embarked_S  

#   0         A/5 21171   7.2500   NaN       False       False        True  

#   1          PC 17599  71.2833   C85        True       False       False  

#   2  STON/O2. 3101282   7.9250   NaN       False       False        True  

#   3            113803  53.1000  C123       False       False        True  

#   4            373450   8.0500   NaN       False       False        True  


"""
最后，我们可以用drop()函数来清除掉与判断完全无关的数据（噪音）
"""

df = df.drop(columns = ['PassengerId', 'Name','Ticket','Cabin'])
print(df.info())  # 输出表格里的所有字段以及对应变量类型
# Output:
#   <class 'pandas.DataFrame'>

#   RangeIndex: 891 entries, 0 to 890

#   Data columns (total 10 columns):

#    #   Column      Non-Null Count  Dtype  

#   ---  ------      --------------  -----  

#    0   Survived    891 non-null    int64  

#    1   Pclass      891 non-null    int64  

#    2   Sex         891 non-null    int64  

#    3   Age         891 non-null    float64

#    4   SibSp       891 non-null    int64  

#    5   Parch       891 non-null    int64  

#    6   Fare        891 non-null    float64

#    7   Embarked_C  891 non-null    bool   

#    8   Embarked_Q  891 non-null    bool   

#    9   Embarked_S  891 non-null    bool   

#   dtypes: bool(3), float64(2), int64(5)

#   memory usage: 51.5 KB

#   None


"""
下一步我们要把特征和标签分开，单独拎出特征和标签
"""

X = df.drop(columns=['Survived'])
y = df['Survived']

print(f"考题 X 的形状：{X.shape} (几百个乘客，每个乘客有几个特征)")
print(f"答案 y 的形状：{y.shape} (几百个 0 或 1 的结局)")
# Output:
#   考题 X 的形状：(891, 9) (几百个乘客，每个乘客有几个特征)

#   答案 y 的形状：(891,) (几百个 0 或 1 的结局)


"""
接下来就是常规的模型训练了
"""

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

X_train, X_val, y_train, y_val = train_test_split(X, y, test_size=0.2, random_state=42)
print(f"用来训练的 X_train: {X_train.shape[0]} 人")
print(f"留作验证的 X_val:   {X_val.shape[0]} 人")

model = LogisticRegression(max_iter=1000)

model.fit(X_train, y_train)
y_pred = model.predict(X_val)

acc = accuracy_score(y_val, y_pred)
print(f"🏆 本地验证集准确率 (Accuracy): {acc * 100:.2f}%")
# Output:
#   用来训练的 X_train: 712 人

#   留作验证的 X_val:   179 人

#   🏆 本地验证集准确率 (Accuracy): 81.01%


"""
下面我们来看一下哪些特征是对逃生有最大正作用的，哪些是对逃生有最大负作用的
"""

import pandas as pd

feature_names = X.columns  # 提取所有的特征，赋值给feature_names，返回的是一个列表
weights = model.coef_[0]  # scikit-learn的权重列表是一个嵌套列表，所以只能用中括号的形式拉取列表

importance_df = pd.DataFrame({
    '特征':feature_names,
    '权重':weights
})

importance_df = importance_df.sort_values(by='权重', ascending=False)
print(importance_df)
# Output:
#              特征        权重

#   1         Sex  2.590228

#   6  Embarked_C  0.118032

#   5        Fare  0.002528

#   7  Embarked_Q -0.027426

#   2         Age -0.030508

#   4       Parch -0.107868

#   3       SibSp -0.293289

#   8  Embarked_S -0.309045

#   0      Pclass -0.935236




================================================
FILE: ML/ML_projects/titanic/train.csv
================================================
PassengerId,Survived,Pclass,Name,Sex,Age,SibSp,Parch,Ticket,Fare,Cabin,Embarked
1,0,3,"Braund, Mr. Owen Harris",male,22,1,0,A/5 21171,7.25,,S
2,1,1,"Cumings, Mrs. John Bradley (Florence Briggs Thayer)",female,38,1,0,PC 17599,71.2833,C85,C
3,1,3,"Heikkinen, Miss. Laina",female,26,0,0,STON/O2. 3101282,7.925,,S
4,1,1,"Futrelle, Mrs. Jacques Heath (Lily May Peel)",female,35,1,0,113803,53.1,C123,S
5,0,3,"Allen, Mr. William Henry",male,35,0,0,373450,8.05,,S
6,0,3,"Moran, Mr. James",male,,0,0,330877,8.4583,,Q
7,0,1,"McCarthy, Mr. Timothy J",male,54,0,0,17463,51.8625,E46,S
8,0,3,"Palsson, Master. Gosta Leonard",male,2,3,1,349909,21.075,,S
9,1,3,"Johnson, Mrs. Oscar W (Elisabeth Vilhelmina Berg)",female,27,0,2,347742,11.1333,,S
10,1,2,"Nasser, Mrs. Nicholas (Adele Achem)",female,14,1,0,237736,30.0708,,C
11,1,3,"Sandstrom, Miss. Marguerite Rut",female,4,1,1,PP 9549,16.7,G6,S
12,1,1,"Bonnell, Miss. Elizabeth",female,58,0,0,113783,26.55,C103,S
13,0,3,"Saundercock, Mr. William Henry",male,20,0,0,A/5. 2151,8.05,,S
14,0,3,"Andersson, Mr. Anders Johan",male,39,1,5,347082,31.275,,S
15,0,3,"Vestrom, Miss. Hulda Amanda Adolfina",female,14,0,0,350406,7.8542,,S
16,1,2,"Hewlett, Mrs. (Mary D Kingcome) ",female,55,0,0,248706,16,,S
17,0,3,"Rice, Master. Eugene",male,2,4,1,382652,29.125,,Q
18,1,2,"Williams, Mr. Charles Eugene",male,,0,0,244373,13,,S
19,0,3,"Vander Planke, Mrs. Julius (Emelia Maria Vandemoortele)",female,31,1,0,345763,18,,S
20,1,3,"Masselmani, Mrs. Fatima",female,,0,0,2649,7.225,,C
21,0,2,"Fynney, Mr. Joseph J",male,35,0,0,239865,26,,S
22,1,2,"Beesley, Mr. Lawrence",male,34,0,0,248698,13,D56,S
23,1,3,"McGowan, Miss. Anna ""Annie""",female,15,0,0,330923,8.0292,,Q
24,1,1,"Sloper, Mr. William Thompson",male,28,0,0,113788,35.5,A6,S
25,0,3,"Palsson, Miss. Torborg Danira",female,8,3,1,349909,21.075,,S
26,1,3,"Asplund, Mrs. Carl Oscar (Selma Augusta Emilia Johansson)",female,38,1,5,347077,31.3875,,S
27,0,3,"Emir, Mr. Farred Chehab",male,,0,0,2631,7.225,,C
28,0,1,"Fortune, Mr. Charles Alexander",male,19,3,2,19950,263,C23 C25 C27,S
29,1,3,"O'Dwyer, Miss. Ellen ""Nellie""",female,,0,0,330959,7.8792,,Q
30,0,3,"Todoroff, Mr. Lalio",male,,0,0,349216,7.8958,,S
31,0,1,"Uruchurtu, Don. Manuel E",male,40,0,0,PC 17601,27.7208,,C
32,1,1,"Spencer, Mrs. William Augustus (Marie Eugenie)",female,,1,0,PC 17569,146.5208,B78,C
33,1,3,"Glynn, Miss. Mary Agatha",female,,0,0,335677,7.75,,Q
34,0,2,"Wheadon, Mr. Edward H",male,66,0,0,C.A. 24579,10.5,,S
35,0,1,"Meyer, Mr. Edgar Joseph",male,28,1,0,PC 17604,82.1708,,C
36,0,1,"Holverson, Mr. Alexander Oskar",male,42,1,0,113789,52,,S
37,1,3,"Mamee, Mr. Hanna",male,,0,0,2677,7.2292,,C
38,0,3,"Cann, Mr. Ernest Charles",male,21,0,0,A./5. 2152,8.05,,S
39,0,3,"Vander Planke, Miss. Augusta Maria",female,18,2,0,345764,18,,S
40,1,3,"Nicola-Yarred, Miss. Jamila",female,14,1,0,2651,11.2417,,C
41,0,3,"Ahlin, Mrs. Johan (Johanna Persdotter Larsson)",female,40,1,0,7546,9.475,,S
42,0,2,"Turpin, Mrs. William John Robert (Dorothy Ann Wonnacott)",female,27,1,0,11668,21,,S
43,0,3,"Kraeff, Mr. Theodor",male,,0,0,349253,7.8958,,C
44,1,2,"Laroche, Miss. Simonne Marie Anne Andree",female,3,1,2,SC/Paris 2123,41.5792,,C
45,1,3,"Devaney, Miss. Margaret Delia",female,19,0,0,330958,7.8792,,Q
46,0,3,"Rogers, Mr. William John",male,,0,0,S.C./A.4. 23567,8.05,,S
47,0,3,"Lennon, Mr. Denis",male,,1,0,370371,15.5,,Q
48,1,3,"O'Driscoll, Miss. Bridget",female,,0,0,14311,7.75,,Q
49,0,3,"Samaan, Mr. Youssef",male,,2,0,2662,21.6792,,C
50,0,3,"Arnold-Franchi, Mrs. Josef (Josefine Franchi)",female,18,1,0,349237,17.8,,S
51,0,3,"Panula, Master. Juha Niilo",male,7,4,1,3101295,39.6875,,S
52,0,3,"Nosworthy, Mr. Richard Cater",male,21,0,0,A/4. 39886,7.8,,S
53,1,1,"Harper, Mrs. Henry Sleeper (Myna Haxtun)",female,49,1,0,PC 17572,76.7292,D33,C
54,1,2,"Faunthorpe, Mrs. Lizzie (Elizabeth Anne Wilkinson)",female,29,1,0,2926,26,,S
55,0,1,"Ostby, Mr. Engelhart Cornelius",male,65,0,1,113509,61.9792,B30,C
56,1,1,"Woolner, Mr. Hugh",male,,0,0,19947,35.5,C52,S
57,1,2,"Rugg, Miss. Emily",female,21,0,0,C.A. 31026,10.5,,S
58,0,3,"Novel, Mr. Mansouer",male,28.5,0,0,2697,7.2292,,C
59,1,2,"West, Miss. Constance Mirium",female,5,1,2,C.A. 34651,27.75,,S
60,0,3,"Goodwin, Master. William Frederick",male,11,5,2,CA 2144,46.9,,S
61,0,3,"Sirayanian, Mr. Orsen",male,22,0,0,2669,7.2292,,C
62,1,1,"Icard, Miss. Amelie",female,38,0,0,113572,80,B28,
63,0,1,"Harris, Mr. Henry Birkhardt",male,45,1,0,36973,83.475,C83,S
64,0,3,"Skoog, Master. Harald",male,4,3,2,347088,27.9,,S
65,0,1,"Stewart, Mr. Albert A",male,,0,0,PC 17605,27.7208,,C
66,1,3,"Moubarek, Master. Gerios",male,,1,1,2661,15.2458,,C
67,1,2,"Nye, Mrs. (Elizabeth Ramell)",female,29,0,0,C.A. 29395,10.5,F33,S
68,0,3,"Crease, Mr. Ernest James",male,19,0,0,S.P. 3464,8.1583,,S
69,1,3,"Andersson, Miss. Erna Alexandra",female,17,4,2,3101281,7.925,,S
70,0,3,"Kink, Mr. Vincenz",male,26,2,0,315151,8.6625,,S
71,0,2,"Jenkin, Mr. Stephen Curnow",male,32,0,0,C.A. 33111,10.5,,S
72,0,3,"Goodwin, Miss. Lillian Amy",female,16,5,2,CA 2144,46.9,,S
73,0,2,"Hood, Mr. Ambrose Jr",male,21,0,0,S.O.C. 14879,73.5,,S
74,0,3,"Chronopoulos, Mr. Apostolos",male,26,1,0,2680,14.4542,,C
75,1,3,"Bing, Mr. Lee",male,32,0,0,1601,56.4958,,S
76,0,3,"Moen, Mr. Sigurd Hansen",male,25,0,0,348123,7.65,F G73,S
77,0,3,"Staneff, Mr. Ivan",male,,0,0,349208,7.8958,,S
78,0,3,"Moutal, Mr. Rahamin Haim",male,,0,0,374746,8.05,,S
79,1,2,"Caldwell, Master. Alden Gates",male,0.83,0,2,248738,29,,S
80,1,3,"Dowdell, Miss. Elizabeth",female,30,0,0,364516,12.475,,S
81,0,3,"Waelens, Mr. Achille",male,22,0,0,345767,9,,S
82,1,3,"Sheerlinck, Mr. Jan Baptist",male,29,0,0,345779,9.5,,S
83,1,3,"McDermott, Miss. Brigdet Delia",female,,0,0,330932,7.7875,,Q
84,0,1,"Carrau, Mr. Francisco M",male,28,0,0,113059,47.1,,S
85,1,2,"Ilett, Miss. Bertha",female,17,0,0,SO/C 14885,10.5,,S
86,1,3,"Backstrom, Mrs. Karl Alfred (Maria Mathilda Gustafsson)",female,33,3,0,3101278,15.85,,S
87,0,3,"Ford, Mr. William Neal",male,16,1,3,W./C. 6608,34.375,,S
88,0,3,"Slocovski, Mr. Selman Francis",male,,0,0,SOTON/OQ 392086,8.05,,S
89,1,1,"Fortune, Miss. Mabel Helen",female,23,3,2,19950,263,C23 C25 C27,S
90,0,3,"Celotti, Mr. Francesco",male,24,0,0,343275,8.05,,S
91,0,3,"Christmann, Mr. Emil",male,29,0,0,343276,8.05,,S
92,0,3,"Andreasson, Mr. Paul Edvin",male,20,0,0,347466,7.8542,,S
93,0,1,"Chaffee, Mr. Herbert Fuller",male,46,1,0,W.E.P. 5734,61.175,E31,S
94,0,3,"Dean, Mr. Bertram Frank",male,26,1,2,C.A. 2315,20.575,,S
95,0,3,"Coxon, Mr. Daniel",male,59,0,0,364500,7.25,,S
96,0,3,"Shorney, Mr. Charles Joseph",male,,0,0,374910,8.05,,S
97,0,1,"Goldschmidt, Mr. George B",male,71,0,0,PC 17754,34.6542,A5,C
98,1,1,"Greenfield, Mr. William Bertram",male,23,0,1,PC 17759,63.3583,D10 D12,C
99,1,2,"Doling, Mrs. John T (Ada Julia Bone)",female,34,0,1,231919,23,,S
100,0,2,"Kantor, Mr. Sinai",male,34,1,0,244367,26,,S
101,0,3,"Petranec, Miss. Matilda",female,28,0,0,349245,7.8958,,S
102,0,3,"Petroff, Mr. Pastcho (""Pentcho"")",male,,0,0,349215,7.8958,,S
103,0,1,"White, Mr. Richard Frasar",male,21,0,1,35281,77.2875,D26,S
104,0,3,"Johansson, Mr. Gustaf Joel",male,33,0,0,7540,8.6542,,S
105,0,3,"Gustafsson, Mr. Anders Vilhelm",male,37,2,0,3101276,7.925,,S
106,0,3,"Mionoff, Mr. Stoytcho",male,28,0,0,349207,7.8958,,S
107,1,3,"Salkjelsvik, Miss. Anna Kristine",female,21,0,0,343120,7.65,,S
108,1,3,"Moss, Mr. Albert Johan",male,,0,0,312991,7.775,,S
109,0,3,"Rekic, Mr. Tido",male,38,0,0,349249,7.8958,,S
110,1,3,"Moran, Miss. Bertha",female,,1,0,371110,24.15,,Q
111,0,1,"Porter, Mr. Walter Chamberlain",male,47,0,0,110465,52,C110,S
112,0,3,"Zabour, Miss. Hileni",female,14.5,1,0,2665,14.4542,,C
113,0,3,"Barton, Mr. David John",male,22,0,0,324669,8.05,,S
114,0,3,"Jussila, Miss. Katriina",female,20,1,0,4136,9.825,,S
115,0,3,"Attalah, Miss. Malake",female,17,0,0,2627,14.4583,,C
116,0,3,"Pekoniemi, Mr. Edvard",male,21,0,0,STON/O 2. 3101294,7.925,,S
117,0,3,"Connors, Mr. Patrick",male,70.5,0,0,370369,7.75,,Q
118,0,2,"Turpin, Mr. William John Robert",male,29,1,0,11668,21,,S
119,0,1,"Baxter, Mr. Quigg Edmond",male,24,0,1,PC 17558,247.5208,B58 B60,C
120,0,3,"Andersson, Miss. Ellis Anna Maria",female,2,4,2,347082,31.275,,S
121,0,2,"Hickman, Mr. Stanley George",male,21,2,0,S.O.C. 14879,73.5,,S
122,0,3,"Moore, Mr. Leonard Charles",male,,0,0,A4. 54510,8.05,,S
123,0,2,"Nasser, Mr. Nicholas",male,32.5,1,0,237736,30.0708,,C
124,1,2,"Webber, Miss. Susan",female,32.5,0,0,27267,13,E101,S
125,0,1,"White, Mr. Percival Wayland",male,54,0,1,35281,77.2875,D26,S
126,1,3,"Nicola-Yarred, Master. Elias",male,12,1,0,2651,11.2417,,C
127,0,3,"McMahon, Mr. Martin",male,,0,0,370372,7.75,,Q
128,1,3,"Madsen, Mr. Fridtjof Arne",male,24,0,0,C 17369,7.1417,,S
129,1,3,"Peter, Miss. Anna",female,,1,1,2668,22.3583,F E69,C
130,0,3,"Ekstrom, Mr. Johan",male,45,0,0,347061,6.975,,S
131,0,3,"Drazenoic, Mr. Jozef",male,33,0,0,349241,7.8958,,C
132,0,3,"Coelho, Mr. Domingos Fernandeo",male,20,0,0,SOTON/O.Q. 3101307,7.05,,S
133,0,3,"Robins, Mrs. Alexander A (Grace Charity Laury)",female,47,1,0,A/5. 3337,14.5,,S
134,1,2,"Weisz, Mrs. Leopold (Mathilde Francoise Pede)",female,29,1,0,228414,26,,S
135,0,2,"Sobey, Mr. Samuel James Hayden",male,25,0,0,C.A. 29178,13,,S
136,0,2,"Richard, Mr. Emile",male,23,0,0,SC/PARIS 2133,15.0458,,C
137,1,1,"Newsom, Miss. Helen Monypeny",female,19,0,2,11752,26.2833,D47,S
138,0,1,"Futrelle, Mr. Jacques Heath",male,37,1,0,113803,53.1,C123,S
139,0,3,"Osen, Mr. Olaf Elon",male,16,0,0,7534,9.2167,,S
140,0,1,"Giglio, Mr. Victor",male,24,0,0,PC 17593,79.2,B86,C
141,0,3,"Boulos, Mrs. Joseph (Sultana)",female,,0,2,2678,15.2458,,C
142,1,3,"Nysten, Miss. Anna Sofia",female,22,0,0,347081,7.75,,S
143,1,3,"Hakkarainen, Mrs. Pekka Pietari (Elin Matilda Dolck)",female,24,1,0,STON/O2. 3101279,15.85,,S
144,0,3,"Burke, Mr. Jeremiah",male,19,0,0,365222,6.75,,Q
145,0,2,"Andrew, Mr. Edgardo Samuel",male,18,0,0,231945,11.5,,S
146,0,2,"Nicholls, Mr. Joseph Charles",male,19,1,1,C.A. 33112,36.75,,S
147,1,3,"Andersson, Mr. August Edvard (""Wennerstrom"")",male,27,0,0,350043,7.7958,,S
148,0,3,"Ford, Miss. Robina Maggie ""Ruby""",female,9,2,2,W./C. 6608,34.375,,S
149,0,2,"Navratil, Mr. Michel (""Louis M Hoffman"")",male,36.5,0,2,230080,26,F2,S
150,0,2,"Byles, Rev. Thomas Roussel Davids",male,42,0,0,244310,13,,S
151,0,2,"Bateman, Rev. Robert James",male,51,0,0,S.O.P. 1166,12.525,,S
152,1,1,"Pears, Mrs. Thomas (Edith Wearne)",female,22,1,0,113776,66.6,C2,S
153,0,3,"Meo, Mr. Alfonzo",male,55.5,0,0,A.5. 11206,8.05,,S
154,0,3,"van Billiard, Mr. Austin Blyler",male,40.5,0,2,A/5. 851,14.5,,S
155,0,3,"Olsen, Mr. Ole Martin",male,,0,0,Fa 265302,7.3125,,S
156,0,1,"Williams, Mr. Charles Duane",male,51,0,1,PC 17597,61.3792,,C
157,1,3,"Gilnagh, Miss. Katherine ""Katie""",female,16,0,0,35851,7.7333,,Q
158,0,3,"Corn, Mr. Harry",male,30,0,0,SOTON/OQ 392090,8.05,,S
159,0,3,"Smiljanic, Mr. Mile",male,,0,0,315037,8.6625,,S
160,0,3,"Sage, Master. Thomas Henry",male,,8,2,CA. 2343,69.55,,S
161,0,3,"Cribb, Mr. John Hatfield",male,44,0,1,371362,16.1,,S
162,1,2,"Watt, Mrs. James (Elizabeth ""Bessie"" Inglis Milne)",female,40,0,0,C.A. 33595,15.75,,S
163,0,3,"Bengtsson, Mr. John Viktor",male,26,0,0,347068,7.775,,S
164,0,3,"Calic, Mr. Jovo",male,17,0,0,315093,8.6625,,S
165,0,3,"Panula, Master. Eino Viljami",male,1,4,1,3101295,39.6875,,S
166,1,3,"Goldsmith, Master. Frank John William ""Frankie""",male,9,0,2,363291,20.525,,S
167,1,1,"Chibnall, Mrs. (Edith Martha Bowerman)",female,,0,1,113505,55,E33,S
168,0,3,"Skoog, Mrs. William (Anna Bernhardina Karlsson)",female,45,1,4,347088,27.9,,S
169,0,1,"Baumann, Mr. John D",male,,0,0,PC 17318,25.925,,S
170,0,3,"Ling, Mr. Lee",male,28,0,0,1601,56.4958,,S
171,0,1,"Van der hoef, Mr. Wyckoff",male,61,0,0,111240,33.5,B19,S
172,0,3,"Rice, Master. Arthur",male,4,4,1,382652,29.125,,Q
173,1,3,"Johnson, Miss. Eleanor Ileen",female,1,1,1,347742,11.1333,,S
174,0,3,"Sivola, Mr. Antti Wilhelm",male,21,0,0,STON/O 2. 3101280,7.925,,S
175,0,1,"Smith, Mr. James Clinch",male,56,0,0,17764,30.6958,A7,C
176,0,3,"Klasen, Mr. Klas Albin",male,18,1,1,350404,7.8542,,S
177,0,3,"Lefebre, Master. Henry Forbes",male,,3,1,4133,25.4667,,S
178,0,1,"Isham, Miss. Ann Elizabeth",female,50,0,0,PC 17595,28.7125,C49,C
179,0,2,"Hale, Mr. Reginald",male,30,0,0,250653,13,,S
180,0,3,"Leonard, Mr. Lionel",male,36,0,0,LINE,0,,S
181,0,3,"Sage, Miss. Constance Gladys",female,,8,2,CA. 2343,69.55,,S
182,0,2,"Pernot, Mr. Rene",male,,0,0,SC/PARIS 2131,15.05,,C
183,0,3,"Asplund, Master. Clarence Gustaf Hugo",male,9,4,2,347077,31.3875,,S
184,1,2,"Becker, Master. Richard F",male,1,2,1,230136,39,F4,S
185,1,3,"Kink-Heilmann, Miss. Luise Gretchen",female,4,0,2,315153,22.025,,S
186,0,1,"Rood, Mr. Hugh Roscoe",male,,0,0,113767,50,A32,S
187,1,3,"O'Brien, Mrs. Thomas (Johanna ""Hannah"" Godfrey)",female,,1,0,370365,15.5,,Q
188,1,1,"Romaine, Mr. Charles Hallace (""Mr C Rolmane"")",male,45,0,0,111428,26.55,,S
189,0,3,"Bourke, Mr. John",male,40,1,1,364849,15.5,,Q
190,0,3,"Turcin, Mr. Stjepan",male,36,0,0,349247,7.8958,,S
191,1,2,"Pinsky, Mrs. (Rosa)",female,32,0,0,234604,13,,S
192,0,2,"Carbines, Mr. William",male,19,0,0,28424,13,,S
193,1,3,"Andersen-Jensen, Miss. Carla Christine Nielsine",female,19,1,0,350046,7.8542,,S
194,1,2,"Navratil, Master. Michel M",male,3,1,1,230080,26,F2,S
195,1,1,"Brown, Mrs. James Joseph (Margaret Tobin)",female,44,0,0,PC 17610,27.7208,B4,C
196,1,1,"Lurette, Miss. Elise",female,58,0,0,PC 17569,146.5208,B80,C
197,0,3,"Mernagh, Mr. Robert",male,,0,0,368703,7.75,,Q
198,0,3,"Olsen, Mr. Karl Siegwart Andreas",male,42,0,1,4579,8.4042,,S
199,1,3,"Madigan, Miss. Margaret ""Maggie""",female,,0,0,370370,7.75,,Q
200,0,2,"Yrois, Miss. Henriette (""Mrs Harbeck"")",female,24,0,0,248747,13,,S
201,0,3,"Vande Walle, Mr. Nestor Cyriel",male,28,0,0,345770,9.5,,S
202,0,3,"Sage, Mr. Frederick",male,,8,2,CA. 2343,69.55,,S
203,0,3,"Johanson, Mr. Jakob Alfred",male,34,0,0,3101264,6.4958,,S
204,0,3,"Youseff, Mr. Gerious",male,45.5,0,0,2628,7.225,,C
205,1,3,"Cohen, Mr. Gurshon ""Gus""",male,18,0,0,A/5 3540,8.05,,S
206,0,3,"Strom, Miss. Telma Matilda",female,2,0,1,347054,10.4625,G6,S
207,0,3,"Backstrom, Mr. Karl Alfred",male,32,1,0,3101278,15.85,,S
208,1,3,"Albimona, Mr. Nassef Cassem",male,26,0,0,2699,18.7875,,C
209,1,3,"Carr, Miss. Helen ""Ellen""",female,16,0,0,367231,7.75,,Q
210,1,1,"Blank, Mr. Henry",male,40,0,0,112277,31,A31,C
211,0,3,"Ali, Mr. Ahmed",male,24,0,0,SOTON/O.Q. 3101311,7.05,,S
212,1,2,"Cameron, Miss. Clear Annie",female,35,0,0,F.C.C. 13528,21,,S
213,0,3,"Perkin, Mr. John Henry",male,22,0,0,A/5 21174,7.25,,S
214,0,2,"Givard, Mr. Hans Kristensen",male,30,0,0,250646,13,,S
215,0,3,"Kiernan, Mr. Philip",male,,1,0,367229,7.75,,Q
216,1,1,"Newell, Miss. Madeleine",female,31,1,0,35273,113.275,D36,C
217,1,3,"Honkanen, Miss. Eliina",female,27,0,0,STON/O2. 3101283,7.925,,S
218,0,2,"Jacobsohn, Mr. Sidney Samuel",male,42,1,0,243847,27,,S
219,1,1,"Bazzani, Miss. Albina",female,32,0,0,11813,76.2917,D15,C
220,0,2,"Harris, Mr. Walter",male,30,0,0,W/C 14208,10.5,,S
221,1,3,"Sunderland, Mr. Victor Francis",male,16,0,0,SOTON/OQ 392089,8.05,,S
222,0,2,"Bracken, Mr. James H",male,27,0,0,220367,13,,S
223,0,3,"Green, Mr. George Henry",male,51,0,0,21440,8.05,,S
224,0,3,"Nenkoff, Mr. Christo",male,,0,0,349234,7.8958,,S
225,1,1,"Hoyt, Mr. Frederick Maxfield",male,38,1,0,19943,90,C93,S
226,0,3,"Berglund, Mr. Karl Ivar Sven",male,22,0,0,PP 4348,9.35,,S
227,1,2,"Mellors, Mr. William John",male,19,0,0,SW/PP 751,10.5,,S
228,0,3,"Lovell, Mr. John Hall (""Henry"")",male,20.5,0,0,A/5 21173,7.25,,S
229,0,2,"Fahlstrom, Mr. Arne Jonas",male,18,0,0,236171,13,,S
230,0,3,"Lefebre, Miss. Mathilde",female,,3,1,4133,25.4667,,S
231,1,1,"Harris, Mrs. Henry Birkhardt (Irene Wallach)",female,35,1,0,36973,83.475,C83,S
232,0,3,"Larsson, Mr. Bengt Edvin",male,29,0,0,347067,7.775,,S
233,0,2,"Sjostedt, Mr. Ernst Adolf",male,59,0,0,237442,13.5,,S
234,1,3,"Asplund, Miss. Lillian Gertrud",female,5,4,2,347077,31.3875,,S
235,0,2,"Leyson, Mr. Robert William Norman",male,24,0,0,C.A. 29566,10.5,,S
236,0,3,"Harknett, Miss. Alice Phoebe",female,,0,0,W./C. 6609,7.55,,S
237,0,2,"Hold, Mr. Stephen",male,44,1,0,26707,26,,S
238,1,2,"Collyer, Miss. Marjorie ""Lottie""",female,8,0,2,C.A. 31921,26.25,,S
239,0,2,"Pengelly, Mr. Frederick William",male,19,0,0,28665,10.5,,S
240,0,2,"Hunt, Mr. George Henry",male,33,0,0,SCO/W 1585,12.275,,S
241,0,3,"Zabour, Miss. Thamine",female,,1,0,2665,14.4542,,C
242,1,3,"Murphy, Miss. Katherine ""Kate""",female,,1,0,367230,15.5,,Q
243,0,2,"Coleridge, Mr. Reginald Charles",male,29,0,0,W./C. 14263,10.5,,S
244,0,3,"Maenpaa, Mr. Matti Alexanteri",male,22,0,0,STON/O 2. 3101275,7.125,,S
245,0,3,"Attalah, Mr. Sleiman",male,30,0,0,2694,7.225,,C
246,0,1,"Minahan, Dr. William Edward",male,44,2,0,19928,90,C78,Q
247,0,3,"Lindahl, Miss. Agda Thorilda Viktoria",female,25,0,0,347071,7.775,,S
248,1,2,"Hamalainen, Mrs. William (Anna)",female,24,0,2,250649,14.5,,S
249,1,1,"Beckwith, Mr. Richard Leonard",male,37,1,1,11751,52.5542,D35,S
250,0,2,"Carter, Rev. Ernest Courtenay",male,54,1,0,244252,26,,S
251,0,3,"Reed, Mr. James George",male,,0,0,362316,7.25,,S
252,0,3,"Strom, Mrs. Wilhelm (Elna Matilda Persson)",female,29,1,1,347054,10.4625,G6,S
253,0,1,"Stead, Mr. William Thomas",male,62,0,0,113514,26.55,C87,S
254,0,3,"Lobb, Mr. William Arthur",male,30,1,0,A/5. 3336,16.1,,S
255,0,3,"Rosblom, Mrs. Viktor (Helena Wilhelmina)",female,41,0,2,370129,20.2125,,S
256,1,3,"Touma, Mrs. Darwis (Hanne Youssef Razi)",female,29,0,2,2650,15.2458,,C
257,1,1,"Thorne, Mrs. Gertrude Maybelle",female,,0,0,PC 17585,79.2,,C
258,1,1,"Cherry, Miss. Gladys",female,30,0,0,110152,86.5,B77,S
259,1,1,"Ward, Miss. Anna",female,35,0,0,PC 17755,512.3292,,C
260,1,2,"Parrish, Mrs. (Lutie Davis)",female,50,0,1,230433,26,,S
261,0,3,"Smith, Mr. Thomas",male,,0,0,384461,7.75,,Q
262,1,3,"Asplund, Master. Edvin Rojj Felix",male,3,4,2,347077,31.3875,,S
263,0,1,"Taussig, Mr. Emil",male,52,1,1,110413,79.65,E67,S
264,0,1,"Harrison, Mr. William",male,40,0,0,112059,0,B94,S
265,0,3,"Henry, Miss. Delia",female,,0,0,382649,7.75,,Q
266,0,2,"Reeves, Mr. David",male,36,0,0,C.A. 17248,10.5,,S
267,0,3,"Panula, Mr. Ernesti Arvid",male,16,4,1,3101295,39.6875,,S
268,1,3,"Persson, Mr. Ernst Ulrik",male,25,1,0,347083,7.775,,S
269,1,1,"Graham, Mrs. William Thompson (Edith Junkins)",female,58,0,1,PC 17582,153.4625,C125,S
270,1,1,"Bissette, Miss. Amelia",female,35,0,0,PC 17760,135.6333,C99,S
271,0,1,"Cairns, Mr. Alexander",male,,0,0,113798,31,,S
272,1,3,"Tornquist, Mr. William Henry",male,25,0,0,LINE,0,,S
273,1,2,"Mellinger, Mrs. (Elizabeth Anne Maidment)",female,41,0,1,250644,19.5,,S
274,0,1,"Natsch, Mr. Charles H",male,37,0,1,PC 17596,29.7,C118,C
275,1,3,"Healy, Miss. Hanora ""Nora""",female,,0,0,370375,7.75,,Q
276,1,1,"Andrews, Miss. Kornelia Theodosia",female,63,1,0,13502,77.9583,D7,S
277,0,3,"Lindblom, Miss. Augusta Charlotta",female,45,0,0,347073,7.75,,S
278,0,2,"Parkes, Mr. Francis ""Frank""",male,,0,0,239853,0,,S
279,0,3,"Rice, Master. Eric",male,7,4,1,382652,29.125,,Q
280,1,3,"Abbott, Mrs. Stanton (Rosa Hunt)",female,35,1,1,C.A. 2673,20.25,,S
281,0,3,"Duane, Mr. Frank",male,65,0,0,336439,7.75,,Q
282,0,3,"Olsson, Mr. Nils Johan Goransson",male,28,0,0,347464,7.8542,,S
283,0,3,"de Pelsmaeker, Mr. Alfons",male,16,0,0,345778,9.5,,S
284,1,3,"Dorking, Mr. Edward Arthur",male,19,0,0,A/5. 10482,8.05,,S
285,0,1,"Smith, Mr. Richard William",male,,0,0,113056,26,A19,S
286,0,3,"Stankovic, Mr. Ivan",male,33,0,0,349239,8.6625,,C
287,1,3,"de Mulder, Mr. Theodore",male,30,0,0,345774,9.5,,S
288,0,3,"Naidenoff, Mr. Penko",male,22,0,0,349206,7.8958,,S
289,1,2,"Hosono, Mr. Masabumi",male,42,0,0,237798,13,,S
290,1,3,"Connolly, Miss. Kate",female,22,0,0,370373,7.75,,Q
291,1,1,"Barber, Miss. Ellen ""Nellie""",female,26,0,0,19877,78.85,,S
292,1,1,"Bishop, Mrs. Dickinson H (Helen Walton)",female,19,1,0,11967,91.0792,B49,C
293,0,2,"Levy, Mr. Rene Jacques",male,36,0,0,SC/Paris 2163,12.875,D,C
294,0,3,"Haas, Miss. Aloisia",female,24,0,0,349236,8.85,,S
295,0,3,"Mineff, Mr. Ivan",male,24,0,0,349233,7.8958,,S
296,0,1,"Lewy, Mr. Ervin G",male,,0,0,PC 17612,27.7208,,C
297,0,3,"Hanna, Mr. Mansour",male,23.5,0,0,2693,7.2292,,C
298,0,1,"Allison, Miss. Helen Loraine",female,2,1,2,113781,151.55,C22 C26,S
299,1,1,"Saalfeld, Mr. Adolphe",male,,0,0,19988,30.5,C106,S
300,1,1,"Baxter, Mrs. James (Helene DeLaudeniere Chaput)",female,50,0,1,PC 17558,247.5208,B58 B60,C
301,1,3,"Kelly, Miss. Anna Katherine ""Annie Kate""",female,,0,0,9234,7.75,,Q
302,1,3,"McCoy, Mr. Bernard",male,,2,0,367226,23.25,,Q
303,0,3,"Johnson, Mr. William Cahoone Jr",male,19,0,0,LINE,0,,S
304,1,2,"Keane, Miss. Nora A",female,,0,0,226593,12.35,E101,Q
305,0,3,"Williams, Mr. Howard Hugh ""Harry""",male,,0,0,A/5 2466,8.05,,S
306,1,1,"Allison, Master. Hudson Trevor",male,0.92,1,2,113781,151.55,C22 C26,S
307,1,1,"Fleming, Miss. Margaret",female,,0,0,17421,110.8833,,C
308,1,1,"Penasco y Castellana, Mrs. Victor de Satode (Maria Josefa Perez de Soto y Vallejo)",female,17,1,0,PC 17758,108.9,C65,C
309,0,2,"Abelson, Mr. Samuel",male,30,1,0,P/PP 3381,24,,C
310,1,1,"Francatelli, Miss. Laura Mabel",female,30,0,0,PC 17485,56.9292,E36,C
311,1,1,"Hays, Miss. Margaret Bechstein",female,24,0,0,11767,83.1583,C54,C
312,1,1,"Ryerson, Miss. Emily Borie",female,18,2,2,PC 17608,262.375,B57 B59 B63 B66,C
313,0,2,"Lahtinen, Mrs. William (Anna Sylfven)",female,26,1,1,250651,26,,S
314,0,3,"Hendekovic, Mr. Ignjac",male,28,0,0,349243,7.8958,,S
315,0,2,"Hart, Mr. Benjamin",male,43,1,1,F.C.C. 13529,26.25,,S
316,1,3,"Nilsson, Miss. Helmina Josefina",female,26,0,0,347470,7.8542,,S
317,1,2,"Kantor, Mrs. Sinai (Miriam Sternin)",female,24,1,0,244367,26,,S
318,0,2,"Moraweck, Dr. Ernest",male,54,0,0,29011,14,,S
319,1,1,"Wick, Miss. Mary Natalie",female,31,0,2,36928,164.8667,C7,S
320,1,1,"Spedden, Mrs. Frederic Oakley (Margaretta Corning Stone)",female,40,1,1,16966,134.5,E34,C
321,0,3,"Dennis, Mr. Samuel",male,22,0,0,A/5 21172,7.25,,S
322,0,3,"Danoff, Mr. Yoto",male,27,0,0,349219,7.8958,,S
323,1,2,"Slayter, Miss. Hilda Mary",female,30,0,0,234818,12.35,,Q
324,1,2,"Caldwell, Mrs. Albert Francis (Sylvia Mae Harbaugh)",female,22,1,1,248738,29,,S
325,0,3,"Sage, Mr. George John Jr",male,,8,2,CA. 2343,69.55,,S
326,1,1,"Young, Miss. Marie Grice",female,36,0,0,PC 17760,135.6333,C32,C
327,0,3,"Nysveen, Mr. Johan Hansen",male,61,0,0,345364,6.2375,,S
328,1,2,"Ball, Mrs. (Ada E Hall)",female,36,0,0,28551,13,D,S
329,1,3,"Goldsmith, Mrs. Frank John (Emily Alice Brown)",female,31,1,1,363291,20.525,,S
330,1,1,"Hippach, Miss. Jean Gertrude",female,16,0,1,111361,57.9792,B18,C
331,1,3,"McCoy, Miss. Agnes",female,,2,0,367226,23.25,,Q
332,0,1,"Partner, Mr. Austen",male,45.5,0,0,113043,28.5,C124,S
333,0,1,"Graham, Mr. George Edward",male,38,0,1,PC 17582,153.4625,C91,S
334,0,3,"Vander Planke, Mr. Leo Edmondus",male,16,2,0,345764,18,,S
335,1,1,"Frauenthal, Mrs. Henry William (Clara Heinsheimer)",female,,1,0,PC 17611,133.65,,S
336,0,3,"Denkoff, Mr. Mitto",male,,0,0,349225,7.8958,,S
337,0,1,"Pears, Mr. Thomas Clinton",male,29,1,0,113776,66.6,C2,S
338,1,1,"Burns, Miss. Elizabeth Margaret",female,41,0,0,16966,134.5,E40,C
339,1,3,"Dahl, Mr. Karl Edwart",male,45,0,0,7598,8.05,,S
340,0,1,"Blackwell, Mr. Stephen Weart",male,45,0,0,113784,35.5,T,S
341,1,2,"Navratil, Master. Edmond Roger",male,2,1,1,230080,26,F2,S
342,1,1,"Fortune, Miss. Alice Elizabeth",female,24,3,2,19950,263,C23 C25 C27,S
343,0,2,"Collander, Mr. Erik Gustaf",male,28,0,0,248740,13,,S
344,0,2,"Sedgwick, Mr. Charles Frederick Waddington",male,25,0,0,244361,13,,S
345,0,2,"Fox, Mr. Stanley Hubert",male,36,0,0,229236,13,,S
346,1,2,"Brown, Miss. Amelia ""Mildred""",female,24,0,0,248733,13,F33,S
347,1,2,"Smith, Miss. Marion Elsie",female,40,0,0,31418,13,,S
348,1,3,"Davison, Mrs. Thomas Henry (Mary E Finck)",female,,1,0,386525,16.1,,S
349,1,3,"Coutts, Master. William Loch ""William""",male,3,1,1,C.A. 37671,15.9,,S
350,0,3,"Dimic, Mr. Jovan",male,42,0,0,315088,8.6625,,S
351,0,3,"Odahl, Mr. Nils Martin",male,23,0,0,7267,9.225,,S
352,0,1,"Williams-Lambert, Mr. Fletcher Fellows",male,,0,0,113510,35,C128,S
353,0,3,"Elias, Mr. Tannous",male,15,1,1,2695,7.2292,,C
354,0,3,"Arnold-Franchi, Mr. Josef",male,25,1,0,349237,17.8,,S
355,0,3,"Yousif, Mr. Wazli",male,,0,0,2647,7.225,,C
356,0,3,"Vanden Steen, Mr. Leo Peter",male,28,0,0,345783,9.5,,S
357,1,1,"Bowerman, Miss. Elsie Edith",female,22,0,1,113505,55,E33,S
358,0,2,"Funk, Miss. Annie Clemmer",female,38,0,0,237671,13,,S
359,1,3,"McGovern, Miss. Mary",female,,0,0,330931,7.8792,,Q
360,1,3,"Mockler, Miss. Helen Mary ""Ellie""",female,,0,0,330980,7.8792,,Q
361,0,3,"Skoog, Mr. Wilhelm",male,40,1,4,347088,27.9,,S
362,0,2,"del Carlo, Mr. Sebastiano",male,29,1,0,SC/PARIS 2167,27.7208,,C
363,0,3,"Barbara, Mrs. (Catherine David)",female,45,0,1,2691,14.4542,,C
364,0,3,"Asim, Mr. Adola",male,35,0,0,SOTON/O.Q. 3101310,7.05,,S
365,0,3,"O'Brien, Mr. Thomas",male,,1,0,370365,15.5,,Q
366,0,3,"Adahl, Mr. Mauritz Nils Martin",male,30,0,0,C 7076,7.25,,S
367,1,1,"Warren, Mrs. Frank Manley (Anna Sophia Atkinson)",female,60,1,0,110813,75.25,D37,C
368,1,3,"Moussa, Mrs. (Mantoura Boulos)",female,,0,0,2626,7.2292,,C
369,1,3,"Jermyn, Miss. Annie",female,,0,0,14313,7.75,,Q
370,1,1,"Aubart, Mme. Leontine Pauline",female,24,0,0,PC 17477,69.3,B35,C
371,1,1,"Harder, Mr. George Achilles",male,25,1,0,11765,55.4417,E50,C
372,0,3,"Wiklund, Mr. Jakob Alfred",male,18,1,0,3101267,6.4958,,S
373,0,3,"Beavan, Mr. William Thomas",male,19,0,0,323951,8.05,,S
374,0,1,"Ringhini, Mr. Sante",male,22,0,0,PC 17760,135.6333,,C
375,0,3,"Palsson, Miss. Stina Viola",female,3,3,1,349909,21.075,,S
376,1,1,"Meyer, Mrs. Edgar Joseph (Leila Saks)",female,,1,0,PC 17604,82.1708,,C
377,1,3,"Landergren, Miss. Aurora Adelia",female,22,0,0,C 7077,7.25,,S
378,0,1,"Widener, Mr. Harry Elkins",male,27,0,2,113503,211.5,C82,C
379,0,3,"Betros, Mr. Tannous",male,20,0,0,2648,4.0125,,C
380,0,3,"Gustafsson, Mr. Karl Gideon",male,19,0,0,347069,7.775,,S
381,1,1,"Bidois, Miss. Rosalie",female,42,0,0,PC 17757,227.525,,C
382,1,3,"Nakid, Miss. Maria (""Mary"")",female,1,0,2,2653,15.7417,,C
383,0,3,"Tikkanen, Mr. Juho",male,32,0,0,STON/O 2. 3101293,7.925,,S
384,1,1,"Holverson, Mrs. Alexander Oskar (Mary Aline Towner)",female,35,1,0,113789,52,,S
385,0,3,"Plotcharsky, Mr. Vasil",male,,0,0,349227,7.8958,,S
386,0,2,"Davies, Mr. Charles Henry",male,18,0,0,S.O.C. 14879,73.5,,S
387,0,3,"Goodwin, Master. Sidney Leonard",male,1,5,2,CA 2144,46.9,,S
388,1,2,"Buss, Miss. Kate",female,36,0,0,27849,13,,S
389,0,3,"Sadlier, Mr. Matthew",male,,0,0,367655,7.7292,,Q
390,1,2,"Lehmann, Miss. Bertha",female,17,0,0,SC 1748,12,,C
391,1,1,"Carter, Mr. William Ernest",male,36,1,2,113760,120,B96 B98,S
392,1,3,"Jansson, Mr. Carl Olof",male,21,0,0,350034,7.7958,,S
393,0,3,"Gustafsson, Mr. Johan Birger",male,28,2,0,3101277,7.925,,S
394,1,1,"Newell, Miss. Marjorie",female,23,1,0,35273,113.275,D36,C
395,1,3,"Sandstrom, Mrs. Hjalmar (Agnes Charlotta Bengtsson)",female,24,0,2,PP 9549,16.7,G6,S
396,0,3,"Johansson, Mr. Erik",male,22,0,0,350052,7.7958,,S
397,0,3,"Olsson, Miss. Elina",female,31,0,0,350407,7.8542,,S
398,0,2,"McKane, Mr. Peter David",male,46,0,0,28403,26,,S
399,0,2,"Pain, Dr. Alfred",male,23,0,0,244278,10.5,,S
400,1,2,"Trout, Mrs. William H (Jessie L)",female,28,0,0,240929,12.65,,S
401,1,3,"Niskanen, Mr. Juha",male,39,0,0,STON/O 2. 3101289,7.925,,S
402,0,3,"Adams, Mr. John",male,26,0,0,341826,8.05,,S
403,0,3,"Jussila, Miss. Mari Aina",female,21,1,0,4137,9.825,,S
404,0,3,"Hakkarainen, Mr. Pekka Pietari",male,28,1,0,STON/O2. 3101279,15.85,,S
405,0,3,"Oreskovic, Miss. Marija",female,20,0,0,315096,8.6625,,S
406,0,2,"Gale, Mr. Shadrach",male,34,1,0,28664,21,,S
407,0,3,"Widegren, Mr. Carl/Charles Peter",male,51,0,0,347064,7.75,,S
408,1,2,"Richards, Master. William Rowe",male,3,1,1,29106,18.75,,S
409,0,3,"Birkeland, Mr. Hans Martin Monsen",male,21,0,0,312992,7.775,,S
410,0,3,"Lefebre, Miss. Ida",female,,3,1,4133,25.4667,,S
411,0,3,"Sdycoff, Mr. Todor",male,,0,0,349222,7.8958,,S
412,0,3,"Hart, Mr. Henry",male,,0,0,394140,6.8583,,Q
413,1,1,"Minahan, Miss. Daisy E",female,33,1,0,19928,90,C78,Q
414,0,2,"Cunningham, Mr. Alfred Fleming",male,,0,0,239853,0,,S
415,1,3,"Sundman, Mr. Johan Julian",male,44,0,0,STON/O 2. 3101269,7.925,,S
416,0,3,"Meek, Mrs. Thomas (Annie Louise Rowley)",female,,0,0,343095,8.05,,S
417,1,2,"Drew, Mrs. James Vivian (Lulu Thorne Christian)",female,34,1,1,28220,32.5,,S
418,1,2,"Silven, Miss. Lyyli Karoliina",female,18,0,2,250652,13,,S
419,0,2,"Matthews, Mr. William John",male,30,0,0,28228,13,,S
420,0,3,"Van Impe, Miss. Catharina",female,10,0,2,345773,24.15,,S
421,0,3,"Gheorgheff, Mr. Stanio",male,,0,0,349254,7.8958,,C
422,0,3,"Charters, Mr. David",male,21,0,0,A/5. 13032,7.7333,,Q
423,0,3,"Zimmerman, Mr. Leo",male,29,0,0,315082,7.875,,S
424,0,3,"Danbom, Mrs. Ernst Gilbert (Anna Sigrid Maria Brogren)",female,28,1,1,347080,14.4,,S
425,0,3,"Rosblom, Mr. Viktor Richard",male,18,1,1,370129,20.2125,,S
426,0,3,"Wiseman, Mr. Phillippe",male,,0,0,A/4. 34244,7.25,,S
427,1,2,"Clarke, Mrs. Charles V (Ada Maria Winfield)",female,28,1,0,2003,26,,S
428,1,2,"Phillips, Miss. Kate Florence (""Mrs Kate Louise Phillips Marshall"")",female,19,0,0,250655,26,,S
429,0,3,"Flynn, Mr. James",male,,0,0,364851,7.75,,Q
430,1,3,"Pickard, Mr. Berk (Berk Trembisky)",male,32,0,0,SOTON/O.Q. 392078,8.05,E10,S
431,1,1,"Bjornstrom-Steffansson, Mr. Mauritz Hakan",male,28,0,0,110564,26.55,C52,S
432,1,3,"Thorneycroft, Mrs. Percival (Florence Kate White)",female,,1,0,376564,16.1,,S
433,1,2,"Louch, Mrs. Charles Alexander (Alice Adelaide Slow)",female,42,1,0,SC/AH 3085,26,,S
434,0,3,"Kallio, Mr. Nikolai Erland",male,17,0,0,STON/O 2. 3101274,7.125,,S
435,0,1,"Silvey, Mr. William Baird",male,50,1,0,13507,55.9,E44,S
436,1,1,"Carter, Miss. Lucile Polk",female,14,1,2,113760,120,B96 B98,S
437,0,3,"Ford, Miss. Doolina Margaret ""Daisy""",female,21,2,2,W./C. 6608,34.375,,S
438,1,2,"Richards, Mrs. Sidney (Emily Hocking)",female,24,2,3,29106,18.75,,S
439,0,1,"Fortune, Mr. Mark",male,64,1,4,19950,263,C23 C25 C27,S
440,0,2,"Kvillner, Mr. Johan Henrik Johannesson",male,31,0,0,C.A. 18723,10.5,,S
441,1,2,"Hart, Mrs. Benjamin (Esther Ada Bloomfield)",female,45,1,1,F.C.C. 13529,26.25,,S
442,0,3,"Hampe, Mr. Leon",male,20,0,0,345769,9.5,,S
443,0,3,"Petterson, Mr. Johan Emil",male,25,1,0,347076,7.775,,S
444,1,2,"Reynaldo, Ms. Encarnacion",female,28,0,0,230434,13,,S
445,1,3,"Johannesen-Bratthammer, Mr. Bernt",male,,0,0,65306,8.1125,,S
446,1,1,"Dodge, Master. Washington",male,4,0,2,33638,81.8583,A34,S
447,1,2,"Mellinger, Miss. Madeleine Violet",female,13,0,1,250644,19.5,,S
448,1,1,"Seward, Mr. Frederic Kimber",male,34,0,0,113794,26.55,,S
449,1,3,"Baclini, Miss. Marie Catherine",female,5,2,1,2666,19.2583,,C
450,1,1,"Peuchen, Major. Arthur Godfrey",male,52,0,0,113786,30.5,C104,S
451,0,2,"West, Mr. Edwy Arthur",male,36,1,2,C.A. 34651,27.75,,S
452,0,3,"Hagland, Mr. Ingvald Olai Olsen",male,,1,0,65303,19.9667,,S
453,0,1,"Foreman, Mr. Benjamin Laventall",male,30,0,0,113051,27.75,C111,C
454,1,1,"Goldenberg, Mr. Samuel L",male,49,1,0,17453,89.1042,C92,C
455,0,3,"Peduzzi, Mr. Joseph",male,,0,0,A/5 2817,8.05,,S
456,1,3,"Jalsevac, Mr. Ivan",male,29,0,0,349240,7.8958,,C
457,0,1,"Millet, Mr. Francis Davis",male,65,0,0,13509,26.55,E38,S
458,1,1,"Kenyon, Mrs. Frederick R (Marion)",female,,1,0,17464,51.8625,D21,S
459,1,2,"Toomey, Miss. Ellen",female,50,0,0,F.C.C. 13531,10.5,,S
460,0,3,"O'Connor, Mr. Maurice",male,,0,0,371060,7.75,,Q
461,1,1,"Anderson, Mr. Harry",male,48,0,0,19952,26.55,E12,S
462,0,3,"Morley, Mr. William",male,34,0,0,364506,8.05,,S
463,0,1,"Gee, Mr. Arthur H",male,47,0,0,111320,38.5,E63,S
464,0,2,"Milling, Mr. Jacob Christian",male,48,0,0,234360,13,,S
465,0,3,"Maisner, Mr. Simon",male,,0,0,A/S 2816,8.05,,S
466,0,3,"Goncalves, Mr. Manuel Estanslas",male,38,0,0,SOTON/O.Q. 3101306,7.05,,S
467,0,2,"Campbell, Mr. William",male,,0,0,239853,0,,S
468,0,1,"Smart, Mr. John Montgomery",male,56,0,0,113792,26.55,,S
469,0,3,"Scanlan, Mr. James",male,,0,0,36209,7.725,,Q
470,1,3,"Baclini, Miss. Helene Barbara",female,0.75,2,1,2666,19.2583,,C
471,0,3,"Keefe, Mr. Arthur",male,,0,0,323592,7.25,,S
472,0,3,"Cacic, Mr. Luka",male,38,0,0,315089,8.6625,,S
473,1,2,"West, Mrs. Edwy Arthur (Ada Mary Worth)",female,33,1,2,C.A. 34651,27.75,,S
474,1,2,"Jerwan, Mrs. Amin S (Marie Marthe Thuillard)",female,23,0,0,SC/AH Basle 541,13.7917,D,C
475,0,3,"Strandberg, Miss. Ida Sofia",female,22,0,0,7553,9.8375,,S
476,0,1,"Clifford, Mr. George Quincy",male,,0,0,110465,52,A14,S
477,0,2,"Renouf, Mr. Peter Henry",male,34,1,0,31027,21,,S
478,0,3,"Braund, Mr. Lewis Richard",male,29,1,0,3460,7.0458,,S
479,0,3,"Karlsson, Mr. Nils August",male,22,0,0,350060,7.5208,,S
480,1,3,"Hirvonen, Miss. Hildur E",female,2,0,1,3101298,12.2875,,S
481,0,3,"Goodwin, Master. Harold Victor",male,9,5,2,CA 2144,46.9,,S
482,0,2,"Frost, Mr. Anthony Wood ""Archie""",male,,0,0,239854,0,,S
483,0,3,"Rouse, Mr. Richard Henry",male,50,0,0,A/5 3594,8.05,,S
484,1,3,"Turkula, Mrs. (Hedwig)",female,63,0,0,4134,9.5875,,S
485,1,1,"Bishop, Mr. Dickinson H",male,25,1,0,11967,91.0792,B49,C
486,0,3,"Lefebre, Miss. Jeannie",female,,3,1,4133,25.4667,,S
487,1,1,"Hoyt, Mrs. Frederick Maxfield (Jane Anne Forby)",female,35,1,0,19943,90,C93,S
488,0,1,"Kent, Mr. Edward Austin",male,58,0,0,11771,29.7,B37,C
489,0,3,"Somerton, Mr. Francis William",male,30,0,0,A.5. 18509,8.05,,S
490,1,3,"Coutts, Master. Eden Leslie ""Neville""",male,9,1,1,C.A. 37671,15.9,,S
491,0,3,"Hagland, Mr. Konrad Mathias Reiersen",male,,1,0,65304,19.9667,,S
492,0,3,"Windelov, Mr. Einar",male,21,0,0,SOTON/OQ 3101317,7.25,,S
493,0,1,"Molson, Mr. Harry Markland",male,55,0,0,113787,30.5,C30,S
494,0,1,"Artagaveytia, Mr. Ramon",male,71,0,0,PC 17609,49.5042,,C
495,0,3,"Stanley, Mr. Edward Roland",male,21,0,0,A/4 45380,8.05,,S
496,0,3,"Yousseff, Mr. Gerious",male,,0,0,2627,14.4583,,C
497,1,1,"Eustis, Miss. Elizabeth Mussey",female,54,1,0,36947,78.2667,D20,C
498,0,3,"Shellard, Mr. Frederick William",male,,0,0,C.A. 6212,15.1,,S
499,0,1,"Allison, Mrs. Hudson J C (Bessie Waldo Daniels)",female,25,1,2,113781,151.55,C22 C26,S
500,0,3,"Svensson, Mr. Olof",male,24,0,0,350035,7.7958,,S
501,0,3,"Calic, Mr. Petar",male,17,0,0,315086,8.6625,,S
502,0,3,"Canavan, Miss. Mary",female,21,0,0,364846,7.75,,Q
503,0,3,"O'Sullivan, Miss. Bridget Mary",female,,0,0,330909,7.6292,,Q
504,0,3,"Laitinen, Miss. Kristina Sofia",female,37,0,0,4135,9.5875,,S
505,1,1,"Maioni, Miss. Roberta",female,16,0,0,110152,86.5,B79,S
506,0,1,"Penasco y Castellana, Mr. Victor de Satode",male,18,1,0,PC 17758,108.9,C65,C
507,1,2,"Quick, Mrs. Frederick Charles (Jane Richards)",female,33,0,2,26360,26,,S
508,1,1,"Bradley, Mr. George (""George Arthur Brayton"")",male,,0,0,111427,26.55,,S
509,0,3,"Olsen, Mr. Henry Margido",male,28,0,0,C 4001,22.525,,S
510,1,3,"Lang, Mr. Fang",male,26,0,0,1601,56.4958,,S
511,1,3,"Daly, Mr. Eugene Patrick",male,29,0,0,382651,7.75,,Q
512,0,3,"Webber, Mr. James",male,,0,0,SOTON/OQ 3101316,8.05,,S
513,1,1,"McGough, Mr. James Robert",male,36,0,0,PC 17473,26.2875,E25,S
514,1,1,"Rothschild, Mrs. Martin (Elizabeth L. Barrett)",female,54,1,0,PC 17603,59.4,,C
515,0,3,"Coleff, Mr. Satio",male,24,0,0,349209,7.4958,,S
516,0,1,"Walker, Mr. William Anderson",male,47,0,0,36967,34.0208,D46,S
517,1,2,"Lemore, Mrs. (Amelia Milley)",female,34,0,0,C.A. 34260,10.5,F33,S
518,0,3,"Ryan, Mr. Patrick",male,,0,0,371110,24.15,,Q
519,1,2,"Angle, Mrs. William A (Florence ""Mary"" Agnes Hughes)",female,36,1,0,226875,26,,S
520,0,3,"Pavlovic, Mr. Stefo",male,32,0,0,349242,7.8958,,S
521,1,1,"Perreault, Miss. Anne",female,30,0,0,12749,93.5,B73,S
522,0,3,"Vovk, Mr. Janko",male,22,0,0,349252,7.8958,,S
523,0,3,"Lahoud, Mr. Sarkis",male,,0,0,2624,7.225,,C
524,1,1,"Hippach, Mrs. Louis Albert (Ida Sophia Fischer)",female,44,0,1,111361,57.9792,B18,C
525,0,3,"Kassem, Mr. Fared",male,,0,0,2700,7.2292,,C
526,0,3,"Farrell, Mr. James",male,40.5,0,0,367232,7.75,,Q
527,1,2,"Ridsdale, Miss. Lucy",female,50,0,0,W./C. 14258,10.5,,S
528,0,1,"Farthing, Mr. John",male,,0,0,PC 17483,221.7792,C95,S
529,0,3,"Salonen, Mr. Johan Werner",male,39,0,0,3101296,7.925,,S
530,0,2,"Hocking, Mr. Richard George",male,23,2,1,29104,11.5,,S
531,1,2,"Quick, Miss. Phyllis May",female,2,1,1,26360,26,,S
532,0,3,"Toufik, Mr. Nakli",male,,0,0,2641,7.2292,,C
533,0,3,"Elias, Mr. Joseph Jr",male,17,1,1,2690,7.2292,,C
534,1,3,"Peter, Mrs. Catherine (Catherine Rizk)",female,,0,2,2668,22.3583,,C
535,0,3,"Cacic, Miss. Marija",female,30,0,0,315084,8.6625,,S
536,1,2,"Hart, Miss. Eva Miriam",female,7,0,2,F.C.C. 13529,26.25,,S
537,0,1,"Butt, Major. Archibald Willingham",male,45,0,0,113050,26.55,B38,S
538,1,1,"LeRoy, Miss. Bertha",female,30,0,0,PC 17761,106.425,,C
539,0,3,"Risien, Mr. Samuel Beard",male,,0,0,364498,14.5,,S
540,1,1,"Frolicher, Miss. Hedwig Margaritha",female,22,0,2,13568,49.5,B39,C
541,1,1,"Crosby, Miss. Harriet R",female,36,0,2,WE/P 5735,71,B22,S
542,0,3,"Andersson, Miss. Ingeborg Constanzia",female,9,4,2,347082,31.275,,S
543,0,3,"Andersson, Miss. Sigrid Elisabeth",female,11,4,2,347082,31.275,,S
544,1,2,"Beane, Mr. Edward",male,32,1,0,2908,26,,S
545,0,1,"Douglas, Mr. Walter Donald",male,50,1,0,PC 17761,106.425,C86,C
546,0,1,"Nicholson, Mr. Arthur Ernest",male,64,0,0,693,26,,S
547,1,2,"Beane, Mrs. Edward (Ethel Clarke)",female,19,1,0,2908,26,,S
548,1,2,"Padro y Manent, Mr. Julian",male,,0,0,SC/PARIS 2146,13.8625,,C
549,0,3,"Goldsmith, Mr. Frank John",male,33,1,1,363291,20.525,,S
550,1,2,"Davies, Master. John Morgan Jr",male,8,1,1,C.A. 33112,36.75,,S
551,1,1,"Thayer, Mr. John Borland Jr",male,17,0,2,17421,110.8833,C70,C
552,0,2,"Sharp, Mr. Percival James R",male,27,0,0,244358,26,,S
553,0,3,"O'Brien, Mr. Timothy",male,,0,0,330979,7.8292,,Q
554,1,3,"Leeni, Mr. Fahim (""Philip Zenni"")",male,22,0,0,2620,7.225,,C
555,1,3,"Ohman, Miss. Velin",female,22,0,0,347085,7.775,,S
556,0,1,"Wright, Mr. George",male,62,0,0,113807,26.55,,S
557,1,1,"Duff Gordon, Lady. (Lucille Christiana Sutherland) (""Mrs Morgan"")",female,48,1,0,11755,39.6,A16,C
558,0,1,"Robbins, Mr. Victor",male,,0,0,PC 17757,227.525,,C
559,1,1,"Taussig, Mrs. Emil (Tillie Mandelbaum)",female,39,1,1,110413,79.65,E67,S
560,1,3,"de Messemaeker, Mrs. Guillaume Joseph (Emma)",female,36,1,0,345572,17.4,,S
561,0,3,"Morrow, Mr. Thomas Rowan",male,,0,0,372622,7.75,,Q
562,0,3,"Sivic, Mr. Husein",male,40,0,0,349251,7.8958,,S
563,0,2,"Norman, Mr. Robert Douglas",male,28,0,0,218629,13.5,,S
564,0,3,"Simmons, Mr. John",male,,0,0,SOTON/OQ 392082,8.05,,S
565,0,3,"Meanwell, Miss. (Marion Ogden)",female,,0,0,SOTON/O.Q. 392087,8.05,,S
566,0,3,"Davies, Mr. Alfred J",male,24,2,0,A/4 48871,24.15,,S
567,0,3,"Stoytcheff, Mr. Ilia",male,19,0,0,349205,7.8958,,S
568,0,3,"Palsson, Mrs. Nils (Alma Cornelia Berglund)",female,29,0,4,349909,21.075,,S
569,0,3,"Doharr, Mr. Tannous",male,,0,0,2686,7.2292,,C
570,1,3,"Jonsson, Mr. Carl",male,32,0,0,350417,7.8542,,S
571,1,2,"Harris, Mr. George",male,62,0,0,S.W./PP 752,10.5,,S
572,1,1,"Appleton, Mrs. Edward Dale (Charlotte Lamson)",female,53,2,0,11769,51.4792,C101,S
573,1,1,"Flynn, Mr. John Irwin (""Irving"")",male,36,0,0,PC 17474,26.3875,E25,S
574,1,3,"Kelly, Miss. Mary",female,,0,0,14312,7.75,,Q
575,0,3,"Rush, Mr. Alfred George John",male,16,0,0,A/4. 20589,8.05,,S
576,0,3,"Patchett, Mr. George",male,19,0,0,358585,14.5,,S
577,1,2,"Garside, Miss. Ethel",female,34,0,0,243880,13,,S
578,1,1,"Silvey, Mrs. William Baird (Alice Munger)",female,39,1,0,13507,55.9,E44,S
579,0,3,"Caram, Mrs. Joseph (Maria Elias)",female,,1,0,2689,14.4583,,C
580,1,3,"Jussila, Mr. Eiriik",male,32,0,0,STON/O 2. 3101286,7.925,,S
581,1,2,"Christy, Miss. Julie Rachel",female,25,1,1,237789,30,,S
582,1,1,"Thayer, Mrs. John Borland (Marian Longstreth Morris)",female,39,1,1,17421,110.8833,C68,C
583,0,2,"Downton, Mr. William James",male,54,0,0,28403,26,,S
584,0,1,"Ross, Mr. John Hugo",male,36,0,0,13049,40.125,A10,C
585,0,3,"Paulner, Mr. Uscher",male,,0,0,3411,8.7125,,C
586,1,1,"Taussig, Miss. Ruth",female,18,0,2,110413,79.65,E68,S
587,0,2,"Jarvis, Mr. John Denzil",male,47,0,0,237565,15,,S
588,1,1,"Frolicher-Stehli, Mr. Maxmillian",male,60,1,1,13567,79.2,B41,C
589,0,3,"Gilinski, Mr. Eliezer",male,22,0,0,14973,8.05,,S
590,0,3,"Murdlin, Mr. Joseph",male,,0,0,A./5. 3235,8.05,,S
591,0,3,"Rintamaki, Mr. Matti",male,35,0,0,STON/O 2. 3101273,7.125,,S
592,1,1,"Stephenson, Mrs. Walter Bertram (Martha Eustis)",female,52,1,0,36947,78.2667,D20,C
593,0,3,"Elsbury, Mr. William James",male,47,0,0,A/5 3902,7.25,,S
594,0,3,"Bourke, Miss. Mary",female,,0,2,364848,7.75,,Q
595,0,2,"Chapman, Mr. John Henry",male,37,1,0,SC/AH 29037,26,,S
596,0,3,"Van Impe, Mr. Jean Baptiste",male,36,1,1,345773,24.15,,S
597,1,2,"Leitch, Miss. Jessie Wills",female,,0,0,248727,33,,S
598,0,3,"Johnson, Mr. Alfred",male,49,0,0,LINE,0,,S
599,0,3,"Boulos, Mr. Hanna",male,,0,0,2664,7.225,,C
600,1,1,"Duff Gordon, Sir. Cosmo Edmund (""Mr Morgan"")",male,49,1,0,PC 17485,56.9292,A20,C
601,1,2,"Jacobsohn, Mrs. Sidney Samuel (Amy Frances Christy)",female,24,2,1,243847,27,,S
602,0,3,"Slabenoff, Mr. Petco",male,,0,0,349214,7.8958,,S
603,0,1,"Harrington, Mr. Charles H",male,,0,0,113796,42.4,,S
604,0,3,"Torber, Mr. Ernst William",male,44,0,0,364511,8.05,,S
605,1,1,"Homer, Mr. Harry (""Mr E Haven"")",male,35,0,0,111426,26.55,,C
606,0,3,"Lindell, Mr. Edvard Bengtsson",male,36,1,0,349910,15.55,,S
607,0,3,"Karaic, Mr. Milan",male,30,0,0,349246,7.8958,,S
608,1,1,"Daniel, Mr. Robert Williams",male,27,0,0,113804,30.5,,S
609,1,2,"Laroche, Mrs. Joseph (Juliette Marie Louise Lafargue)",female,22,1,2,SC/Paris 2123,41.5792,,C
610,1,1,"Shutes, Miss. Elizabeth W",female,40,0,0,PC 17582,153.4625,C125,S
611,0,3,"Andersson, Mrs. Anders Johan (Alfrida Konstantia Brogren)",female,39,1,5,347082,31.275,,S
612,0,3,"Jardin, Mr. Jose Neto",male,,0,0,SOTON/O.Q. 3101305,7.05,,S
613,1,3,"Murphy, Miss. Margaret Jane",female,,1,0,367230,15.5,,Q
614,0,3,"Horgan, Mr. John",male,,0,0,370377,7.75,,Q
615,0,3,"Brocklebank, Mr. William Alfred",male,35,0,0,364512,8.05,,S
616,1,2,"Herman, Miss. Alice",female,24,1,2,220845,65,,S
617,0,3,"Danbom, Mr. Ernst Gilbert",male,34,1,1,347080,14.4,,S
618,0,3,"Lobb, Mrs. William Arthur (Cordelia K Stanlick)",female,26,1,0,A/5. 3336,16.1,,S
619,1,2,"Becker, Miss. Marion Louise",female,4,2,1,230136,39,F4,S
620,0,2,"Gavey, Mr. Lawrence",male,26,0,0,31028,10.5,,S
621,0,3,"Yasbeck, Mr. Antoni",male,27,1,0,2659,14.4542,,C
622,1,1,"Kimball, Mr. Edwin Nelson Jr",male,42,1,0,11753,52.5542,D19,S
623,1,3,"Nakid, Mr. Sahid",male,20,1,1,2653,15.7417,,C
624,0,3,"Hansen, Mr. Henry Damsgaard",male,21,0,0,350029,7.8542,,S
625,0,3,"Bowen, Mr. David John ""Dai""",male,21,0,0,54636,16.1,,S
626,0,1,"Sutton, Mr. Frederick",male,61,0,0,36963,32.3208,D50,S
627,0,2,"Kirkland, Rev. Charles Leonard",male,57,0,0,219533,12.35,,Q
628,1,1,"Longley, Miss. Gretchen Fiske",female,21,0,0,13502,77.9583,D9,S
629,0,3,"Bostandyeff, Mr. Guentcho",male,26,0,0,349224,7.8958,,S
630,0,3,"O'Connell, Mr. Patrick D",male,,0,0,334912,7.7333,,Q
631,1,1,"Barkworth, Mr. Algernon Henry Wilson",male,80,0,0,27042,30,A23,S
632,0,3,"Lundahl, Mr. Johan Svensson",male,51,0,0,347743,7.0542,,S
633,1,1,"Stahelin-Maeglin, Dr. Max",male,32,0,0,13214,30.5,B50,C
634,0,1,"Parr, Mr. William Henry Marsh",male,,0,0,112052,0,,S
635,0,3,"Skoog, Miss. Mabel",female,9,3,2,347088,27.9,,S
636,1,2,"Davis, Miss. Mary",female,28,0,0,237668,13,,S
637,0,3,"Leinonen, Mr. Antti Gustaf",male,32,0,0,STON/O 2. 3101292,7.925,,S
638,0,2,"Collyer, Mr. Harvey",male,31,1,1,C.A. 31921,26.25,,S
639,0,3,"Panula, Mrs. Juha (Maria Emilia Ojala)",female,41,0,5,3101295,39.6875,,S
640,0,3,"Thorneycroft, Mr. Percival",male,,1,0,376564,16.1,,S
641,0,3,"Jensen, Mr. Hans Peder",male,20,0,0,350050,7.8542,,S
642,1,1,"Sagesser, Mlle. Emma",female,24,0,0,PC 17477,69.3,B35,C
643,0,3,"Skoog, Miss. Margit Elizabeth",female,2,3,2,347088,27.9,,S
644,1,3,"Foo, Mr. Choong",male,,0,0,1601,56.4958,,S
645,1,3,"Baclini, Miss. Eugenie",female,0.75,2,1,2666,19.2583,,C
646,1,1,"Harper, Mr. Henry Sleeper",male,48,1,0,PC 17572,76.7292,D33,C
647,0,3,"Cor, Mr. Liudevit",male,19,0,0,349231,7.8958,,S
648,1,1,"Simonius-Blumer, Col. Oberst Alfons",male,56,0,0,13213,35.5,A26,C
649,0,3,"Willey, Mr. Edward",male,,0,0,S.O./P.P. 751,7.55,,S
650,1,3,"Stanley, Miss. Amy Zillah Elsie",female,23,0,0,CA. 2314,7.55,,S
651,0,3,"Mitkoff, Mr. Mito",male,,0,0,349221,7.8958,,S
652,1,2,"Doling, Miss. Elsie",female,18,0,1,231919,23,,S
653,0,3,"Kalvik, Mr. Johannes Halvorsen",male,21,0,0,8475,8.4333,,S
654,1,3,"O'Leary, Miss. Hanora ""Norah""",female,,0,0,330919,7.8292,,Q
655,0,3,"Hegarty, Miss. Hanora ""Nora""",female,18,0,0,365226,6.75,,Q
656,0,2,"Hickman, Mr. Leonard Mark",male,24,2,0,S.O.C. 14879,73.5,,S
657,0,3,"Radeff, Mr. Alexander",male,,0,0,349223,7.8958,,S
658,0,3,"Bourke, Mrs. John (Catherine)",female,32,1,1,364849,15.5,,Q
659,0,2,"Eitemiller, Mr. George Floyd",male,23,0,0,29751,13,,S
660,0,1,"Newell, Mr. Arthur Webster",male,58,0,2,35273,113.275,D48,C
661,1,1,"Frauenthal, Dr. Henry William",male,50,2,0,PC 17611,133.65,,S
662,0,3,"Badt, Mr. Mohamed",male,40,0,0,2623,7.225,,C
663,0,1,"Colley, Mr. Edward Pomeroy",male,47,0,0,5727,25.5875,E58,S
664,0,3,"Coleff, Mr. Peju",male,36,0,0,349210,7.4958,,S
665,1,3,"Lindqvist, Mr. Eino William",male,20,1,0,STON/O 2. 3101285,7.925,,S
666,0,2,"Hickman, Mr. Lewis",male,32,2,0,S.O.C. 14879,73.5,,S
667,0,2,"Butler, Mr. Reginald Fenton",male,25,0,0,234686,13,,S
668,0,3,"Rommetvedt, Mr. Knud Paust",male,,0,0,312993,7.775,,S
669,0,3,"Cook, Mr. Jacob",male,43,0,0,A/5 3536,8.05,,S
670,1,1,"Taylor, Mrs. Elmer Zebley (Juliet Cummins Wright)",female,,1,0,19996,52,C126,S
671,1,2,"Brown, Mrs. Thomas William Solomon (Elizabeth Catherine Ford)",female,40,1,1,29750,39,,S
672,0,1,"Davidson, Mr. Thornton",male,31,1,0,F.C. 12750,52,B71,S
673,0,2,"Mitchell, Mr. Henry Michael",male,70,0,0,C.A. 24580,10.5,,S
674,1,2,"Wilhelms, Mr. Charles",male,31,0,0,244270,13,,S
675,0,2,"Watson, Mr. Ennis Hastings",male,,0,0,239856,0,,S
676,0,3,"Edvardsson, Mr. Gustaf Hjalmar",male,18,0,0,349912,7.775,,S
677,0,3,"Sawyer, Mr. Frederick Charles",male,24.5,0,0,342826,8.05,,S
678,1,3,"Turja, Miss. Anna Sofia",female,18,0,0,4138,9.8417,,S
679,0,3,"Goodwin, Mrs. Frederick (Augusta Tyler)",female,43,1,6,CA 2144,46.9,,S
680,1,1,"Cardeza, Mr. Thomas Drake Martinez",male,36,0,1,PC 17755,512.3292,B51 B53 B55,C
681,0,3,"Peters, Miss. Katie",female,,0,0,330935,8.1375,,Q
682,1,1,"Hassab, Mr. Hammad",male,27,0,0,PC 17572,76.7292,D49,C
683,0,3,"Olsvigen, Mr. Thor Anderson",male,20,0,0,6563,9.225,,S
684,0,3,"Goodwin, Mr. Charles Edward",male,14,5,2,CA 2144,46.9,,S
685,0,2,"Brown, Mr. Thomas William Solomon",male,60,1,1,29750,39,,S
686,0,2,"Laroche, Mr. Joseph Philippe Lemercier",male,25,1,2,SC/Paris 2123,41.5792,,C
687,0,3,"Panula, Mr. Jaako Arnold",male,14,4,1,3101295,39.6875,,S
688,0,3,"Dakic, Mr. Branko",male,19,0,0,349228,10.1708,,S
689,0,3,"Fischer, Mr. Eberhard Thelander",male,18,0,0,350036,7.7958,,S
690,1,1,"Madill, Miss. Georgette Alexandra",female,15,0,1,24160,211.3375,B5,S
691,1,1,"Dick, Mr. Albert Adrian",male,31,1,0,17474,57,B20,S
692,1,3,"Karun, Miss. Manca",female,4,0,1,349256,13.4167,,C
693,1,3,"Lam, Mr. Ali",male,,0,0,1601,56.4958,,S
694,0,3,"Saad, Mr. Khalil",male,25,0,0,2672,7.225,,C
695,0,1,"Weir, Col. John",male,60,0,0,113800,26.55,,S
696,0,2,"Chapman, Mr. Charles Henry",male,52,0,0,248731,13.5,,S
697,0,3,"Kelly, Mr. James",male,44,0,0,363592,8.05,,S
698,1,3,"Mullens, Miss. Katherine ""Katie""",female,,0,0,35852,7.7333,,Q
699,0,1,"Thayer, Mr. John Borland",male,49,1,1,17421,110.8833,C68,C
700,0,3,"Humblen, Mr. Adolf Mathias Nicolai Olsen",male,42,0,0,348121,7.65,F G63,S
701,1,1,"Astor, Mrs. John Jacob (Madeleine Talmadge Force)",female,18,1,0,PC 17757,227.525,C62 C64,C
702,1,1,"Silverthorne, Mr. Spencer Victor",male,35,0,0,PC 17475,26.2875,E24,S
703,0,3,"Barbara, Miss. Saiide",female,18,0,1,2691,14.4542,,C
704,0,3,"Gallagher, Mr. Martin",male,25,0,0,36864,7.7417,,Q
705,0,3,"Hansen, Mr. Henrik Juul",male,26,1,0,350025,7.8542,,S
706,0,2,"Morley, Mr. Henry Samuel (""Mr Henry Marshall"")",male,39,0,0,250655,26,,S
707,1,2,"Kelly, Mrs. Florence ""Fannie""",female,45,0,0,223596,13.5,,S
708,1,1,"Calderhead, Mr. Edward Pennington",male,42,0,0,PC 17476,26.2875,E24,S
709,1,1,"Cleaver, Miss. Alice",female,22,0,0,113781,151.55,,S
710,1,3,"Moubarek, Master. Halim Gonios (""William George"")",male,,1,1,2661,15.2458,,C
711,1,1,"Mayne, Mlle. Berthe Antonine (""Mrs de Villiers"")",female,24,0,0,PC 17482,49.5042,C90,C
712,0,1,"Klaber, Mr. Herman",male,,0,0,113028,26.55,C124,S
713,1,1,"Taylor, Mr. Elmer Zebley",male,48,1,0,19996,52,C126,S
714,0,3,"Larsson, Mr. August Viktor",male,29,0,0,7545,9.4833,,S
715,0,2,"Greenberg, Mr. Samuel",male,52,0,0,250647,13,,S
716,0,3,"Soholt, Mr. Peter Andreas Lauritz Andersen",male,19,0,0,348124,7.65,F G73,S
717,1,1,"Endres, Miss. Caroline Louise",female,38,0,0,PC 17757,227.525,C45,C
718,1,2,"Troutt, Miss. Edwina Celia ""Winnie""",female,27,0,0,34218,10.5,E101,S
719,0,3,"McEvoy, Mr. Michael",male,,0,0,36568,15.5,,Q
720,0,3,"Johnson, Mr. Malkolm Joackim",male,33,0,0,347062,7.775,,S
721,1,2,"Harper, Miss. Annie Jessie ""Nina""",female,6,0,1,248727,33,,S
722,0,3,"Jensen, Mr. Svend Lauritz",male,17,1,0,350048,7.0542,,S
723,0,2,"Gillespie, Mr. William Henry",male,34,0,0,12233,13,,S
724,0,2,"Hodges, Mr. Henry Price",male,50,0,0,250643,13,,S
725,1,1,"Chambers, Mr. Norman Campbell",male,27,1,0,113806,53.1,E8,S
726,0,3,"Oreskovic, Mr. Luka",male,20,0,0,315094,8.6625,,S
727,1,2,"Renouf, Mrs. Peter Henry (Lillian Jefferys)",female,30,3,0,31027,21,,S
728,1,3,"Mannion, Miss. Margareth",female,,0,0,36866,7.7375,,Q
729,0,2,"Bryhl, Mr. Kurt Arnold Gottfrid",male,25,1,0,236853,26,,S
730,0,3,"Ilmakangas, Miss. Pieta Sofia",female,25,1,0,STON/O2. 3101271,7.925,,S
731,1,1,"Allen, Miss. Elisabeth Walton",female,29,0,0,24160,211.3375,B5,S
732,0,3,"Hassan, Mr. Houssein G N",male,11,0,0,2699,18.7875,,C
733,0,2,"Knight, Mr. Robert J",male,,0,0,239855,0,,S
734,0,2,"Berriman, Mr. William John",male,23,0,0,28425,13,,S
735,0,2,"Troupiansky, Mr. Moses Aaron",male,23,0,0,233639,13,,S
736,0,3,"Williams, Mr. Leslie",male,28.5,0,0,54636,16.1,,S
737,0,3,"Ford, Mrs. Edward (Margaret Ann Watson)",female,48,1,3,W./C. 6608,34.375,,S
738,1,1,"Lesurer, Mr. Gustave J",male,35,0,0,PC 17755,512.3292,B101,C
739,0,3,"Ivanoff, Mr. Kanio",male,,0,0,349201,7.8958,,S
740,0,3,"Nankoff, Mr. Minko",male,,0,0,349218,7.8958,,S
741,1,1,"Hawksford, Mr. Walter James",male,,0,0,16988,30,D45,S
742,0,1,"Cavendish, Mr. Tyrell William",male,36,1,0,19877,78.85,C46,S
743,1,1,"Ryerson, Miss. Susan Parker ""Suzette""",female,21,2,2,PC 17608,262.375,B57 B59 B63 B66,C
744,0,3,"McNamee, Mr. Neal",male,24,1,0,376566,16.1,,S
745,1,3,"Stranden, Mr. Juho",male,31,0,0,STON/O 2. 3101288,7.925,,S
746,0,1,"Crosby, Capt. Edward Gifford",male,70,1,1,WE/P 5735,71,B22,S
747,0,3,"Abbott, Mr. Rossmore Edward",male,16,1,1,C.A. 2673,20.25,,S
748,1,2,"Sinkkonen, Miss. Anna",female,30,0,0,250648,13,,S
749,0,1,"Marvin, Mr. Daniel Warner",male,19,1,0,113773,53.1,D30,S
750,0,3,"Connaghton, Mr. Michael",male,31,0,0,335097,7.75,,Q
751,1,2,"Wells, Miss. Joan",female,4,1,1,29103,23,,S
752,1,3,"Moor, Master. Meier",male,6,0,1,392096,12.475,E121,S
753,0,3,"Vande Velde, Mr. Johannes Joseph",male,33,0,0,345780,9.5,,S
754,0,3,"Jonkoff, Mr. Lalio",male,23,0,0,349204,7.8958,,S
755,1,2,"Herman, Mrs. Samuel (Jane Laver)",female,48,1,2,220845,65,,S
756,1,2,"Hamalainen, Master. Viljo",male,0.67,1,1,250649,14.5,,S
757,0,3,"Carlsson, Mr. August Sigfrid",male,28,0,0,350042,7.7958,,S
758,0,2,"Bailey, Mr. Percy Andrew",male,18,0,0,29108,11.5,,S
759,0,3,"Theobald, Mr. Thomas Leonard",male,34,0,0,363294,8.05,,S
760,1,1,"Rothes, the Countess. of (Lucy Noel Martha Dyer-Edwards)",female,33,0,0,110152,86.5,B77,S
761,0,3,"Garfirth, Mr. John",male,,0,0,358585,14.5,,S
762,0,3,"Nirva, Mr. Iisakki Antino Aijo",male,41,0,0,SOTON/O2 3101272,7.125,,S
763,1,3,"Barah, Mr. Hanna Assi",male,20,0,0,2663,7.2292,,C
764,1,1,"Carter, Mrs. William Ernest (Lucile Polk)",female,36,1,2,113760,120,B96 B98,S
765,0,3,"Eklund, Mr. Hans Linus",male,16,0,0,347074,7.775,,S
766,1,1,"Hogeboom, Mrs. John C (Anna Andrews)",female,51,1,0,13502,77.9583,D11,S
767,0,1,"Brewe, Dr. Arthur Jackson",male,,0,0,112379,39.6,,C
768,0,3,"Mangan, Miss. Mary",female,30.5,0,0,364850,7.75,,Q
769,0,3,"Moran, Mr. Daniel J",male,,1,0,371110,24.15,,Q
770,0,3,"Gronnestad, Mr. Daniel Danielsen",male,32,0,0,8471,8.3625,,S
771,0,3,"Lievens, Mr. Rene Aime",male,24,0,0,345781,9.5,,S
772,0,3,"Jensen, Mr. Niels Peder",male,48,0,0,350047,7.8542,,S
773,0,2,"Mack, Mrs. (Mary)",female,57,0,0,S.O./P.P. 3,10.5,E77,S
774,0,3,"Elias, Mr. Dibo",male,,0,0,2674,7.225,,C
775,1,2,"Hocking, Mrs. Elizabeth (Eliza Needs)",female,54,1,3,29105,23,,S
776,0,3,"Myhrman, Mr. Pehr Fabian Oliver Malkolm",male,18,0,0,347078,7.75,,S
777,0,3,"Tobin, Mr. Roger",male,,0,0,383121,7.75,F38,Q
778,1,3,"Emanuel, Miss. Virginia Ethel",female,5,0,0,364516,12.475,,S
779,0,3,"Kilgannon, Mr. Thomas J",male,,0,0,36865,7.7375,,Q
780,1,1,"Robert, Mrs. Edward Scott (Elisabeth Walton McMillan)",female,43,0,1,24160,211.3375,B3,S
781,1,3,"Ayoub, Miss. Banoura",female,13,0,0,2687,7.2292,,C
782,1,1,"Dick, Mrs. Albert Adrian (Vera Gillespie)",female,17,1,0,17474,57,B20,S
783,0,1,"Long, Mr. Milton Clyde",male,29,0,0,113501,30,D6,S
784,0,3,"Johnston, Mr. Andrew G",male,,1,2,W./C. 6607,23.45,,S
785,0,3,"Ali, Mr. William",male,25,0,0,SOTON/O.Q. 3101312,7.05,,S
786,0,3,"Harmer, Mr. Abraham (David Lishin)",male,25,0,0,374887,7.25,,S
787,1,3,"Sjoblom, Miss. Anna Sofia",female,18,0,0,3101265,7.4958,,S
788,0,3,"Rice, Master. George Hugh",male,8,4,1,382652,29.125,,Q
789,1,3,"Dean, Master. Bertram Vere",male,1,1,2,C.A. 2315,20.575,,S
790,0,1,"Guggenheim, Mr. Benjamin",male,46,0,0,PC 17593,79.2,B82 B84,C
791,0,3,"Keane, Mr. Andrew ""Andy""",male,,0,0,12460,7.75,,Q
792,0,2,"Gaskell, Mr. Alfred",male,16,0,0,239865,26,,S
793,0,3,"Sage, Miss. Stella Anna",female,,8,2,CA. 2343,69.55,,S
794,0,1,"Hoyt, Mr. William Fisher",male,,0,0,PC 17600,30.6958,,C
795,0,3,"Dantcheff, Mr. Ristiu",male,25,0,0,349203,7.8958,,S
796,0,2,"Otter, Mr. Richard",male,39,0,0,28213,13,,S
797,1,1,"Leader, Dr. Alice (Farnham)",female,49,0,0,17465,25.9292,D17,S
798,1,3,"Osman, Mrs. Mara",female,31,0,0,349244,8.6833,,S
799,0,3,"Ibrahim Shawah, Mr. Yousseff",male,30,0,0,2685,7.2292,,C
800,0,3,"Van Impe, Mrs. Jean Baptiste (Rosalie Paula Govaert)",female,30,1,1,345773,24.15,,S
801,0,2,"Ponesell, Mr. Martin",male,34,0,0,250647,13,,S
802,1,2,"Collyer, Mrs. Harvey (Charlotte Annie Tate)",female,31,1,1,C.A. 31921,26.25,,S
803,1,1,"Carter, Master. William Thornton II",male,11,1,2,113760,120,B96 B98,S
804,1,3,"Thomas, Master. Assad Alexander",male,0.42,0,1,2625,8.5167,,C
805,1,3,"Hedman, Mr. Oskar Arvid",male,27,0,0,347089,6.975,,S
806,0,3,"Johansson, Mr. Karl Johan",male,31,0,0,347063,7.775,,S
807,0,1,"Andrews, Mr. Thomas Jr",male,39,0,0,112050,0,A36,S
808,0,3,"Pettersson, Miss. Ellen Natalia",female,18,0,0,347087,7.775,,S
809,0,2,"Meyer, Mr. August",male,39,0,0,248723,13,,S
810,1,1,"Chambers, Mrs. Norman Campbell (Bertha Griggs)",female,33,1,0,113806,53.1,E8,S
811,0,3,"Alexander, Mr. William",male,26,0,0,3474,7.8875,,S
812,0,3,"Lester, Mr. James",male,39,0,0,A/4 48871,24.15,,S
813,0,2,"Slemen, Mr. Richard James",male,35,0,0,28206,10.5,,S
814,0,3,"Andersson, Miss. Ebba Iris Alfrida",female,6,4,2,347082,31.275,,S
815,0,3,"Tomlin, Mr. Ernest Portage",male,30.5,0,0,364499,8.05,,S
816,0,1,"Fry, Mr. Richard",male,,0,0,112058,0,B102,S
817,0,3,"Heininen, Miss. Wendla Maria",female,23,0,0,STON/O2. 3101290,7.925,,S
818,0,2,"Mallet, Mr. Albert",male,31,1,1,S.C./PARIS 2079,37.0042,,C
819,0,3,"Holm, Mr. John Fredrik Alexander",male,43,0,0,C 7075,6.45,,S
820,0,3,"Skoog, Master. Karl Thorsten",male,10,3,2,347088,27.9,,S
821,1,1,"Hays, Mrs. Charles Melville (Clara Jennings Gregg)",female,52,1,1,12749,93.5,B69,S
822,1,3,"Lulic, Mr. Nikola",male,27,0,0,315098,8.6625,,S
823,0,1,"Reuchlin, Jonkheer. John George",male,38,0,0,19972,0,,S
824,1,3,"Moor, Mrs. (Beila)",female,27,0,1,392096,12.475,E121,S
825,0,3,"Panula, Master. Urho Abraham",male,2,4,1,3101295,39.6875,,S
826,0,3,"Flynn, Mr. John",male,,0,0,368323,6.95,,Q
827,0,3,"Lam, Mr. Len",male,,0,0,1601,56.4958,,S
828,1,2,"Mallet, Master. Andre",male,1,0,2,S.C./PARIS 2079,37.0042,,C
829,1,3,"McCormack, Mr. Thomas Joseph",male,,0,0,367228,7.75,,Q
830,1,1,"Stone, Mrs. George Nelson (Martha Evelyn)",female,62,0,0,113572,80,B28,
831,1,3,"Yasbeck, Mrs. Antoni (Selini Alexander)",female,15,1,0,2659,14.4542,,C
832,1,2,"Richards, Master. George Sibley",male,0.83,1,1,29106,18.75,,S
833,0,3,"Saad, Mr. Amin",male,,0,0,2671,7.2292,,C
834,0,3,"Augustsson, Mr. Albert",male,23,0,0,347468,7.8542,,S
835,0,3,"Allum, Mr. Owen George",male,18,0,0,2223,8.3,,S
836,1,1,"Compton, Miss. Sara Rebecca",female,39,1,1,PC 17756,83.1583,E49,C
837,0,3,"Pasic, Mr. Jakob",male,21,0,0,315097,8.6625,,S
838,0,3,"Sirota, Mr. Maurice",male,,0,0,392092,8.05,,S
839,1,3,"Chip, Mr. Chang",male,32,0,0,1601,56.4958,,S
840,1,1,"Marechal, Mr. Pierre",male,,0,0,11774,29.7,C47,C
841,0,3,"Alhomaki, Mr. Ilmari Rudolf",male,20,0,0,SOTON/O2 3101287,7.925,,S
842,0,2,"Mudd, Mr. Thomas Charles",male,16,0,0,S.O./P.P. 3,10.5,,S
843,1,1,"Serepeca, Miss. Augusta",female,30,0,0,113798,31,,C
844,0,3,"Lemberopolous, Mr. Peter L",male,34.5,0,0,2683,6.4375,,C
845,0,3,"Culumovic, Mr. Jeso",male,17,0,0,315090,8.6625,,S
846,0,3,"Abbing, Mr. Anthony",male,42,0,0,C.A. 5547,7.55,,S
847,0,3,"Sage, Mr. Douglas Bullen",male,,8,2,CA. 2343,69.55,,S
848,0,3,"Markoff, Mr. Marin",male,35,0,0,349213,7.8958,,C
849,0,2,"Harper, Rev. John",male,28,0,1,248727,33,,S
850,1,1,"Goldenberg, Mrs. Samuel L (Edwiga Grabowska)",female,,1,0,17453,89.1042,C92,C
851,0,3,"Andersson, Master. Sigvard Harald Elias",male,4,4,2,347082,31.275,,S
852,0,3,"Svensson, Mr. Johan",male,74,0,0,347060,7.775,,S
853,0,3,"Boulos, Miss. Nourelain",female,9,1,1,2678,15.2458,,C
854,1,1,"Lines, Miss. Mary Conover",female,16,0,1,PC 17592,39.4,D28,S
855,0,2,"Carter, Mrs. Ernest Courtenay (Lilian Hughes)",female,44,1,0,244252,26,,S
856,1,3,"Aks, Mrs. Sam (Leah Rosen)",female,18,0,1,392091,9.35,,S
857,1,1,"Wick, Mrs. George Dennick (Mary Hitchcock)",female,45,1,1,36928,164.8667,,S
858,1,1,"Daly, Mr. Peter Denis ",male,51,0,0,113055,26.55,E17,S
859,1,3,"Baclini, Mrs. Solomon (Latifa Qurban)",female,24,0,3,2666,19.2583,,C
860,0,3,"Razi, Mr. Raihed",male,,0,0,2629,7.2292,,C
861,0,3,"Hansen, Mr. Claus Peter",male,41,2,0,350026,14.1083,,S
862,0,2,"Giles, Mr. Frederick Edward",male,21,1,0,28134,11.5,,S
863,1,1,"Swift, Mrs. Frederick Joel (Margaret Welles Barron)",female,48,0,0,17466,25.9292,D17,S
864,0,3,"Sage, Miss. Dorothy Edith ""Dolly""",female,,8,2,CA. 2343,69.55,,S
865,0,2,"Gill, Mr. John William",male,24,0,0,233866,13,,S
866,1,2,"Bystrom, Mrs. (Karolina)",female,42,0,0,236852,13,,S
867,1,2,"Duran y More, Miss. Asuncion",female,27,1,0,SC/PARIS 2149,13.8583,,C
868,0,1,"Roebling, Mr. Washington Augustus II",male,31,0,0,PC 17590,50.4958,A24,S
869,0,3,"van Melkebeke, Mr. Philemon",male,,0,0,345777,9.5,,S
870,1,3,"Johnson, Master. Harold Theodor",male,4,1,1,347742,11.1333,,S
871,0,3,"Balkic, Mr. Cerin",male,26,0,0,349248,7.8958,,S
872,1,1,"Beckwith, Mrs. Richard Leonard (Sallie Monypeny)",female,47,1,1,11751,52.5542,D35,S
873,0,1,"Carlsson, Mr. Frans Olof",male,33,0,0,695,5,B51 B53 B55,S
874,0,3,"Vander Cruyssen, Mr. Victor",male,47,0,0,345765,9,,S
875,1,2,"Abelson, Mrs. Samuel (Hannah Wizosky)",female,28,1,0,P/PP 3381,24,,C
876,1,3,"Najib, Miss. Adele Kiamie ""Jane""",female,15,0,0,2667,7.225,,C
877,0,3,"Gustafsson, Mr. Alfred Ossian",male,20,0,0,7534,9.8458,,S
878,0,3,"Petroff, Mr. Nedelio",male,19,0,0,349212,7.8958,,S
879,0,3,"Laleff, Mr. Kristo",male,,0,0,349217,7.8958,,S
880,1,1,"Potter, Mrs. Thomas Jr (Lily Alexenia Wilson)",female,56,0,1,11767,83.1583,C50,C
881,1,2,"Shelley, Mrs. William (Imanita Parrish Hall)",female,25,0,1,230433,26,,S
882,0,3,"Markun, Mr. Johann",male,33,0,0,349257,7.8958,,S
883,0,3,"Dahlberg, Miss. Gerda Ulrika",female,22,0,0,7552,10.5167,,S
884,0,2,"Banfield, Mr. Frederick James",male,28,0,0,C.A./SOTON 34068,10.5,,S
885,0,3,"Sutehall, Mr. Henry Jr",male,25,0,0,SOTON/OQ 392076,7.05,,S
886,0,3,"Rice, Mrs. William (Margaret Norton)",female,39,0,5,382652,29.125,,Q
887,0,2,"Montvila, Rev. Juozas",male,27,0,0,211536,13,,S
888,1,1,"Graham, Miss. Margaret Edith",female,19,0,0,112053,30,B42,S
889,0,3,"Johnston, Miss. Catherine Helen ""Carrie""",female,,1,2,W./C. 6607,23.45,,S
890,1,1,"Behr, Mr. Karl Howell",male,26,0,0,111369,30,C148,C
891,0,3,"Dooley, Mr. Patrick",male,32,0,0,370376,7.75,,Q


