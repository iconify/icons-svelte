<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_8h3-bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_8h3-bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:water-reservoir" {...props}></Icon>
