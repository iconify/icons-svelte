<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz1rqjboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz1rqjboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:traffic-cone-solid" {...props}></Icon>
