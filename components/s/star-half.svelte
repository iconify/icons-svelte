<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6z9mmb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":416};
const content = `<path class="m6z9mmb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:star-half" {...props}></Icon>
