<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvlu8fesh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gvlu8fesh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:toll-booth" {...props}></Icon>
