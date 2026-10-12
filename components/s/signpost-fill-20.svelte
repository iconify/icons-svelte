<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz7t-3bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dz7t-3bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:signpost-fill-20" {...props}></Icon>
