<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s48v5lbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s48v5lbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-alt" {...props}></Icon>
