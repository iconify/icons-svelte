<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loxnei52m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="loxnei52m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:temperature-3" {...props}></Icon>
