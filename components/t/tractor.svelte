<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owc4c2bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="owc4c2bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tractor" {...props}></Icon>
