<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkcvembuk.css';
import '../../css/a/au89ljb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkcvembuk"/><path class="au89ljb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:stormcloud" {...props}></Icon>
