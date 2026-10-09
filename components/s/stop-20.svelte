<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4v4lk0-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v4v4lk0-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stop-20" {...props}></Icon>
