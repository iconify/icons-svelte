<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8sbr7vkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8sbr7vkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:water-drop-fill" {...props}></Icon>
