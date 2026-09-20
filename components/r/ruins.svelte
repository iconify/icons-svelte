<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iao01gbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iao01gbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:ruins" {...props}></Icon>
