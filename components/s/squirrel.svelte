<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elaoyvwug.css';
import '../../css/q/qre15k4lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="elaoyvwug"/><path class="qre15k4lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:squirrel" {...props}></Icon>
