<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz71x_bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hz71x_bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:virtual-reality" {...props}></Icon>
