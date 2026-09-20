<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s61wtolnf.css';
import '../../css/g/gw0rxtbgf.css';
import '../../css/u/u89algnwl.css';
import '../../css/q/qnv6w8b5v.css';
import '../../css/o/o_1k7bbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="s61wtolnf"/><path class="gw0rxtbgf"/><path class="u89algnwl"/><path class="qnv6w8b5v"/><path class="o_1k7bbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:sled" {...props}></Icon>
