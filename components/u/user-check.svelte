<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhn3ibcer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lhn3ibcer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-check" {...props}></Icon>
