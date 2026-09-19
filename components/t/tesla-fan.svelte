<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9zfnyb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9zfnyb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-fan" {...props}></Icon>
