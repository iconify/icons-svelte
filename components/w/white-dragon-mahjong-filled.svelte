<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkt0gbpax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zkt0gbpax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-dragon-mahjong-filled" {...props}></Icon>
