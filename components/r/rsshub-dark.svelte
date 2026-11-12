<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dir6rysvf.css';
import '../../css/a/ab03k5swc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dir6rysvf"/><path class="ab03k5swc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rsshub-dark" {...props}></Icon>
