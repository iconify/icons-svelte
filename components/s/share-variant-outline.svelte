<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwz9-f8wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwz9-f8wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:share-variant-outline" {...props}></Icon>
