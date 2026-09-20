<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bafyibbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bafyibbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:volume-mute-fill" {...props}></Icon>
