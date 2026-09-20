<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsp8lu-gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsp8lu-gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-circle-fill" {...props}></Icon>
