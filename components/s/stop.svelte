<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg36c1b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="kg36c1b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:stop" {...props}></Icon>
