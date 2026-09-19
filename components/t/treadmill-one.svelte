<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx30rb9t.css';
import '../../css/f/fezu9jvay.css';
import '../../css/a/a4tcz4b4u.css';
import '../../css/u/ukcu5rbys.css';
import '../../css/w/wefwctbsn.css';
import '../../css/b/bsvsyqvtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="fezu9jvay"/><path class="a4tcz4b4u"/><path class="ukcu5rbys"/><path class="wefwctbsn"/><path class="bsvsyqvtx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:treadmill-one" {...props}></Icon>
