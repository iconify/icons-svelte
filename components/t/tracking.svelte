<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz5jssbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz5jssbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:tracking" {...props}></Icon>
