<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvs_acwfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gvs_acwfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-horizontal" {...props}></Icon>
