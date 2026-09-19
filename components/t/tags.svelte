<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umeg4vy6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="umeg4vy6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tags" {...props}></Icon>
