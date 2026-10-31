<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t__ggnbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t__ggnbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:truck-fast-fill-round" {...props}></Icon>
