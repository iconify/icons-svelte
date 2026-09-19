<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/i/i4xydol5b.css';
import '../../css/c/c9yt0g5nq.css';
import '../../css/s/s04bc1zdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="i4xydol5b"/><path class="c9yt0g5nq"/><path class="s04bc1zdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ws-1x1" {...props}></Icon>
