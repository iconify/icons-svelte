<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnyufmwwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnyufmwwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:zap-square-fill" {...props}></Icon>
