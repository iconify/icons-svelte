<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evarvxj2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evarvxj2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:share-1" {...props}></Icon>
