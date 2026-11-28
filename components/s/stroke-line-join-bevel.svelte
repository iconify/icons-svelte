<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obv-dzbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obv-dzbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stroke-line-join-bevel" {...props}></Icon>
