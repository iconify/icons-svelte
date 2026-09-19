<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc4-grm-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc4-grm-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scan-heart" {...props}></Icon>
