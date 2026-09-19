<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2bjk7byt.css';
import '../../css/c/c33hiv2aq.css';
import '../../css/s/srb0o_b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2bjk7byt"/><path class="c33hiv2aq"/><path class="srb0o_b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:rugbyfootball" {...props}></Icon>
