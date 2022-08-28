const HandleSubmit = async () => {
        if (email && password) {
            await fetch("https://example.com/data/login", {
                method: "POST",
                headers: {
                    "Content-Type": "application/json",
                    Accept: "application/json",
                },
                body: JSON.stringify({
                    email: email,
                    password: password,
                }),
            })
                .then((res) => res.json())
                .then(async (res) => {
                    if (res.status === true) {
                        //action if true
                        navigation.navigate("Home");
                    } else {
                        //else
                        alert(res.message);
                    }
                }),[];
        }
    };
