<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oygcpqbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oygcpqbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:stretch" {...props}></Icon>
