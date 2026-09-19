<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3e-qgj5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c3e-qgj5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thumbtack" {...props}></Icon>
