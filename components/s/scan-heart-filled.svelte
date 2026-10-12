<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytrgcm7bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytrgcm7bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scan-heart-filled" {...props}></Icon>
