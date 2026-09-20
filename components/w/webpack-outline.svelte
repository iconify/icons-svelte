<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcnqgbyfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wcnqgbyfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:webpack-outline" {...props}></Icon>
