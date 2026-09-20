<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz92cqnqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz92cqnqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:y-skew-line" {...props}></Icon>
