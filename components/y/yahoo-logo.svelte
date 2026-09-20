<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sui-unf4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sui-unf4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:yahoo-logo" {...props}></Icon>
