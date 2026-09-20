<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyxpwnb2l.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zyxpwnb2l"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-square-flag" {...props}></Icon>
