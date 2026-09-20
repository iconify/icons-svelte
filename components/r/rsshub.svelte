<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjn-m4mbs.css';
import '../../css/y/yrit3k1ll.css';
import '../../css/j/jm-3xzqde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjn-m4mbs"/><path class="yrit3k1ll"/><circle class="jm-3xzqde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rsshub" {...props}></Icon>
