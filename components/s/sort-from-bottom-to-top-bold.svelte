<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipovzzbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipovzzbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-bottom-to-top-bold" {...props}></Icon>
