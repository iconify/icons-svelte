<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_zxwmmbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_zxwmmbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stroke-top" {...props}></Icon>
