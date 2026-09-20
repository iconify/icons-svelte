<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3giacbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3giacbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:weather-wind-flow-6" {...props}></Icon>
