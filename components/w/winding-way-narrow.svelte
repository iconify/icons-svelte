<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4sy2kbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j4sy2kbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:winding-way-narrow" {...props}></Icon>
