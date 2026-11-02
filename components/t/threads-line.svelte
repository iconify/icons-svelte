<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz0c64buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz0c64buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:threads-line" {...props}></Icon>
