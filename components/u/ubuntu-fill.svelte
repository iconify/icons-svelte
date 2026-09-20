<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbvgox5fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbvgox5fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ubuntu-fill" {...props}></Icon>
