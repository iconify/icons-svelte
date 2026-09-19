<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pab9xkbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pab9xkbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-snow-filled" {...props}></Icon>
