<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sinukt6es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sinukt6es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:screen-off-outline" {...props}></Icon>
