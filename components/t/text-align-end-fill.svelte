<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c52ptkc9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c52ptkc9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-align-end-fill" {...props}></Icon>
