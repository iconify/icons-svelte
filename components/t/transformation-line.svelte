<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6ui_zbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6ui_zbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transformation-line" {...props}></Icon>
