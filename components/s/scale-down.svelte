<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uidk0bb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uidk0bb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:scale-down" {...props}></Icon>
