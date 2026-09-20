<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5tda9tam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5tda9tam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shield-half" {...props}></Icon>
