<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft2tfpb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ft2tfpb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:snowplow" {...props}></Icon>
