<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb6b2hb8b.css';
import '../../css/g/gcoha---j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb6b2hb8b"/><path class="gcoha---j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:web-check" {...props}></Icon>
