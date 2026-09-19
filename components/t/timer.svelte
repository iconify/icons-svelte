<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5fo0f5ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g5fo0f5ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:timer" {...props}></Icon>
