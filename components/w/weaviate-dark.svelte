<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2rhl-nvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2rhl-nvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weaviate-dark" {...props}></Icon>
