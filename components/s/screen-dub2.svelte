<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzc9eyb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="uzc9eyb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-dub2" {...props}></Icon>
