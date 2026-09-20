<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyxq9bb-b.css';
import '../../css/r/r6p1cia5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pyxq9bb-b"/><path clip-rule="evenodd" class="r6p1cia5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:subtitle" {...props}></Icon>
