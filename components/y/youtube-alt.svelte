<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2y8962pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="n2y8962pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:youtube-alt" {...props}></Icon>
