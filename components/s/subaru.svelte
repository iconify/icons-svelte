<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_k4p1q0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_k4p1q0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:subaru" {...props}></Icon>
