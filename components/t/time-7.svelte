<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilad_8boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ilad_8boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-7" {...props}></Icon>
