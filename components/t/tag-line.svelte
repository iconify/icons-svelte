<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhnz1-bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhnz1-bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-line" {...props}></Icon>
