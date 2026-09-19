<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw9wxrrim.css';
import '../../css/j/jlz7a01mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fw9wxrrim"/><path class="jlz7a01mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sleuthspy" {...props}></Icon>
