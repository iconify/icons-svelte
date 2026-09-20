<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5cjirboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5cjirboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-forward-2-line" {...props}></Icon>
