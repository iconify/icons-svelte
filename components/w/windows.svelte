<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txtnrsm5l.css';
import '../../css/v/vgxjb1-7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="txtnrsm5l"/><path class="vgxjb1-7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:windows" {...props}></Icon>
