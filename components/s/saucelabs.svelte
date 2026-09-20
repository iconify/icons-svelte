<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if170pbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if170pbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:saucelabs" {...props}></Icon>
