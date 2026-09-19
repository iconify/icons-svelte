<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awdcmv7pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awdcmv7pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sun-moon" {...props}></Icon>
