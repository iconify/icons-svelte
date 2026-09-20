<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra19rmbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ra19rmbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tactile-map" {...props}></Icon>
