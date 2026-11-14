<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0bbmrrth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0bbmrrth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:thumbs-down" {...props}></Icon>
