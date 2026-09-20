<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atr8lybzg.css';
import '../../css/q/qbrel2bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atr8lybzg"/><path class="qbrel2bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-man-focus-bold" {...props}></Icon>
