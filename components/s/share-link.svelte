<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep_htdb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ep_htdb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:share-link" {...props}></Icon>
