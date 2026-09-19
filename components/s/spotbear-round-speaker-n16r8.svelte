<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okzh9cbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okzh9cbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:spotbear-round-speaker-n16r8" {...props}></Icon>
