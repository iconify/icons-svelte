<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgpeb1bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jgpeb1bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:terminal-solid" {...props}></Icon>
