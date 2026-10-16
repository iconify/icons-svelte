<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge6gn80ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ge6gn80ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:unlink-20" {...props}></Icon>
