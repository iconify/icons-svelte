<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dalre-d-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dalre-d-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:route-x-solid" {...props}></Icon>
