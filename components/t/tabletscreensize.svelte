<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js_8mh9rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="js_8mh9rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tabletscreensize" {...props}></Icon>
