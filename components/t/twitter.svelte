<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxn_06esw.css';
import '../../css/z/zq5w5wbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lxn_06esw"/><path class="zq5w5wbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:twitter" {...props}></Icon>
