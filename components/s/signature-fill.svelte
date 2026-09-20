<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fszddsb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fszddsb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-fill" {...props}></Icon>
