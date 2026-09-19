<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9af0yl0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q9af0yl0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:welcome-widgets-menus" {...props}></Icon>
