<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra1hklkrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ra1hklkrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:tiktok-solid" {...props}></Icon>
