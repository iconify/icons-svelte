<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q73zmyaty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q73zmyaty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-camera" {...props}></Icon>
