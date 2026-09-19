<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4l0qm4sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4l0qm4sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:serverless" {...props}></Icon>
