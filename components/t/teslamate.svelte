<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prptthbtt.css';
import '../../css/z/zo-mdg_qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prptthbtt"/><path class="zo-mdg_qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teslamate" {...props}></Icon>
