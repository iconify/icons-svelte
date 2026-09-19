<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvkdqm3az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xvkdqm3az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tag" {...props}></Icon>
