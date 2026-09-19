<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjf3h00br.css';
import '../../css/j/jm0mfbcid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wjf3h00br"/><path class="jm0mfbcid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:strategy-play" {...props}></Icon>
