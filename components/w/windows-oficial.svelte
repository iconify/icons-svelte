<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei_fgltjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei_fgltjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:windows-oficial" {...props}></Icon>
