<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw8wwbnil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw8wwbnil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wine-solid" {...props}></Icon>
