<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k66dz5bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k66dz5bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarefive" {...props}></Icon>
