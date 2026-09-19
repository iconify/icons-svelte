<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03tt64we.css';
import '../../css/g/gocezb5zs.css';
import '../../css/c/cv7o1ybwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w03tt64we"/><path class="gocezb5zs"/><path class="cv7o1ybwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitesunsmallcloud" {...props}></Icon>
