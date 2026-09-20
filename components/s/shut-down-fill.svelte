<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb7yk1dfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb7yk1dfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:shut-down-fill" {...props}></Icon>
