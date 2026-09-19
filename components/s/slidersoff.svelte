<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv9d3zbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gv9d3zbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:slidersoff" {...props}></Icon>
