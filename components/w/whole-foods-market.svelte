<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw_bnfbfv.css';
import '../../css/q/q5r6g9iuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":684.206};
const content = `<path class="qw_bnfbfv"/><path class="q5r6g9iuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whole-foods-market" {...props}></Icon>
