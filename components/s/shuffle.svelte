<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dopxjy2hi.css';
import '../../css/r/rs80463iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dopxjy2hi"/><path class="rs80463iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shuffle" {...props}></Icon>
