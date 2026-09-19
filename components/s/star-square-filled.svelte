<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsl_4ebcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsl_4ebcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:star-square-filled" {...props}></Icon>
