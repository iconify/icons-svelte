<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3wp3gbjk.css';
import '../../css/o/opai67bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t3wp3gbjk"/><path class="opai67bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-hex" {...props}></Icon>
