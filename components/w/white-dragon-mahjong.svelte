<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufvr3ut2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ufvr3ut2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-dragon-mahjong" {...props}></Icon>
