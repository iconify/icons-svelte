<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8nmfubyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8nmfubyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zones-areas-second-floor" {...props}></Icon>
