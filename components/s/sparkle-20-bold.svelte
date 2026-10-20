<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc8ay19in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jc8ay19in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkle-20-bold" {...props}></Icon>
