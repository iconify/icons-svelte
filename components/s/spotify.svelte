<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh03e8bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vh03e8bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:spotify" {...props}></Icon>
