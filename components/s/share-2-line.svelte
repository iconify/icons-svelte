<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxwz7_bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwz7_bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-2-line" {...props}></Icon>
