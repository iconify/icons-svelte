<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1d7gwudk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1d7gwudk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-fill" {...props}></Icon>
