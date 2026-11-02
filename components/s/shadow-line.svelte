<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-beybbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-beybbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shadow-line" {...props}></Icon>
