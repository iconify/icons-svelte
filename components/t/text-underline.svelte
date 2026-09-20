<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkg9mnbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkg9mnbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:text-underline" {...props}></Icon>
