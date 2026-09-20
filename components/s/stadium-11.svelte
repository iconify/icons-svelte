<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdg4rh5wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jdg4rh5wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:stadium-11" {...props}></Icon>
