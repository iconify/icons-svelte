<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg7t42bnk.css';
import '../../css/u/ustelzbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg7t42bnk"/><path class="ustelzbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:zap-circle-fill" {...props}></Icon>
