<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5ta4hb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h5ta4hb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stop-16" {...props}></Icon>
