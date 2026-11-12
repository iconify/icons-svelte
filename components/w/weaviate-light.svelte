<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg8csnzhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cg8csnzhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weaviate-light" {...props}></Icon>
