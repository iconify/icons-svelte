<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvomvxbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="pvomvxbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:snowplow" {...props}></Icon>
