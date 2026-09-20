<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqfje-b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqfje-b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:unfold-less-horizontal" {...props}></Icon>
