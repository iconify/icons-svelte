<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybl66cczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybl66cczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-diamond-solid" {...props}></Icon>
