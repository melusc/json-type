# Snapshot report for `test/end-to-end.ts`

The actual snapshot is saved in `end-to-end.ts.snap`.

Generated by [AVA](https://avajs.dev).

## jsonDts

> Snapshot 1

    `type X = {␊
    	y: number;␊
    };␊
    ␊
    type T1 = {␊
    	x: X;␊
    };␊
    ␊
    type T0 = T1[];␊
    `

> Snapshot 2

    `type X2 = {␊
    	y: number;␊
    };␊
    ␊
    type X1 = {␊
    	x: X2;␊
    };␊
    ␊
    type X = X1[];␊
    `

> Snapshot 3

    `type X = {␊
    	y: number;␊
    };␊
    ␊
    type Y1 = {␊
    	x: X;␊
    };␊
    ␊
    type Y = Y1[];␊
    `

> Snapshot 4

    `type X = {␊
    	y: number;␊
    };␊
    ␊
    type T1 = {␊
    	x: X;␊
    };␊
    ␊
    type T = T1[];␊
    `

> Snapshot 5

    `type T1 = {␊
    	x: number;␊
    };␊
    ␊
    type T = T1[];␊
    `

> Snapshot 6

    `type T = {␊
    	x: number;␊
    };␊
    `

> Snapshot 7

    `type T1 = {␊
    	t: number;␊
    };␊
    ␊
    type T = {␊
    	t: T1;␊
    };␊
    `
