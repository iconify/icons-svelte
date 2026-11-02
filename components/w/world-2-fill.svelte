<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b71c6cbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b71c6cbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-2-fill" {...props}></Icon>
