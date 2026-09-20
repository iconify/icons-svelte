<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0xmr68qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0xmr68qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-2-linear" {...props}></Icon>
