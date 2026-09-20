<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcfi8vkuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcfi8vkuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sprinkler-variant" {...props}></Icon>
