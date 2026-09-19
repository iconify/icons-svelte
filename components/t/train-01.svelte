<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pkkrpvzse.css';
import '../../css/p/pvnxvnhrw.css';
import '../../css/q/qqm9ydb9o.css';
import '../../css/x/xvzcmmbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pkkrpvzse"/><path class="pvnxvnhrw"/><path class="qqm9ydb9o"/><path class="xvzcmmbio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:train-01" {...props}></Icon>
