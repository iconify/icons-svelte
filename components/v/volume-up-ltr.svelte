<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfvn_dgph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wfvn_dgph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:volume-up-ltr" {...props}></Icon>
