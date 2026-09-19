<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc4vrv0rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lc4vrv0rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:window-maximize" {...props}></Icon>
