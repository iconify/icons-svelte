<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsy5554rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsy5554rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-3-line" {...props}></Icon>
