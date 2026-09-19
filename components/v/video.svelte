<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syg5edbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="syg5edbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:video" {...props}></Icon>
