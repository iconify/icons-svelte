<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1hrowb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t1hrowb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag" {...props}></Icon>
