<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jon1cz6hx.css';
import '../../css/l/lv3b0kbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jon1cz6hx"/><path class="lv3b0kbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uber" {...props}></Icon>
