<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5wv_8bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g5wv_8bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:upload" {...props}></Icon>
