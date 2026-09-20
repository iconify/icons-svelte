<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4xrj7b1v.css';
import '../../css/f/fxwu97ass.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4xrj7b1v"/><path class="fxwu97ass"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:timetagger" {...props}></Icon>
