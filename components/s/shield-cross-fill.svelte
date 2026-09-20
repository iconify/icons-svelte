<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi0xw016q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi0xw016q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:shield-cross-fill" {...props}></Icon>
