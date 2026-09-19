<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m06hvcsal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m06hvcsal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ulanzi-tc001" {...props}></Icon>
