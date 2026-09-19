<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ljvfbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ljvfbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-resonate" {...props}></Icon>
