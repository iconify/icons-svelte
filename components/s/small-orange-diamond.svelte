<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m76gx5b6o.css';
import '../../css/l/ll5nhre1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="m76gx5b6o"/><path class="ll5nhre1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:small-orange-diamond" {...props}></Icon>
