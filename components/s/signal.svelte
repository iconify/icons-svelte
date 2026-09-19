<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d37s1yb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="d37s1yb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:signal" {...props}></Icon>
