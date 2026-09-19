<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8cnuve7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8cnuve7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:three-finger-03" {...props}></Icon>
