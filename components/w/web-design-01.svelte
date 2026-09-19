<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe7l5qbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe7l5qbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:web-design-01" {...props}></Icon>
