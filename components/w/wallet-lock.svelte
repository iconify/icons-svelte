<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7fmvbbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7fmvbbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wallet-lock" {...props}></Icon>
