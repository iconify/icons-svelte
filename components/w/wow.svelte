<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozvl01bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozvl01bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wow" {...props}></Icon>
