<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glx4dwbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glx4dwbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:text-direction-rtl" {...props}></Icon>
