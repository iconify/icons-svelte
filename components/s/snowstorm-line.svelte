<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgv33zbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgv33zbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowstorm-line" {...props}></Icon>
