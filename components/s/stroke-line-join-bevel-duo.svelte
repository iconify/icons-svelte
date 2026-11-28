<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5mmyei8x.css';
import '../../css/o/obv-dzbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5mmyei8x secondary"/><path class="obv-dzbot primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stroke-line-join-bevel-duo" {...props}></Icon>
