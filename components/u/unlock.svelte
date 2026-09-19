<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7tbccbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="u7tbccbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:unlock" {...props}></Icon>
