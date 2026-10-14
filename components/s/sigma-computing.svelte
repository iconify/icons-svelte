<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trkm4uhtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":32};
const content = `<path class="trkm4uhtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sigma-computing" {...props}></Icon>
