<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce4x6tx7w.css';
import '../../css/w/w0za-obmf.css';
import '../../css/t/tgr0ac0hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ce4x6tx7w"/><path class="w0za-obmf"/><path class="tgr0ac0hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:swift-wordmark" {...props}></Icon>
