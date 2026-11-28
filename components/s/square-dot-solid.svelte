<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfrdicc-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfrdicc-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-dot-solid" {...props}></Icon>
