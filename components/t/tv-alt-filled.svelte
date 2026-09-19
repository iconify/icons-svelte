<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isbbe3e6v.css';
import '../../css/y/ynshwsq7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isbbe3e6v"/><rect class="ynshwsq7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tv-alt-filled" {...props}></Icon>
