<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9g545mxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9g545mxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-forward-2-fill" {...props}></Icon>
