<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arac5xnmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arac5xnmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ruler-dimension-line-filled" {...props}></Icon>
