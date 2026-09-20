<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxbw-6bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxbw-6bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xeta" {...props}></Icon>
