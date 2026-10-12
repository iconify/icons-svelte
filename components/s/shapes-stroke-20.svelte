<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utoyqy2ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="utoyqy2ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-stroke-20" {...props}></Icon>
