<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8uf_sm9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8uf_sm9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-left-04" {...props}></Icon>
