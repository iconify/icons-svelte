<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbd0fcccq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rbd0fcccq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:rounded-rectangle" {...props}></Icon>
