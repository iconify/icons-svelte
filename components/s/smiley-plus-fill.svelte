<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gal76s2ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gal76s2ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:smiley-plus-fill" {...props}></Icon>
