<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-8wrey9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-8wrey9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:welcome-write-blog" {...props}></Icon>
