<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7lr1yx6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="y7lr1yx6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:signal" {...props}></Icon>
