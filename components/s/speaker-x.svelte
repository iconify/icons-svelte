<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhx7cdbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhx7cdbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:speaker-x" {...props}></Icon>
