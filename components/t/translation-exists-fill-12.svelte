<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-xwh2pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r0-xwh2pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-exists-fill-12" {...props}></Icon>
