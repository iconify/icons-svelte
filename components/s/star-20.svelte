<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjuaf1bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qjuaf1bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-20" {...props}></Icon>
