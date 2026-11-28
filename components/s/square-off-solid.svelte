<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi0upab2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0upab2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-off-solid" {...props}></Icon>
