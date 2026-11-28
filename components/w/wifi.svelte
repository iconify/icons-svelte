<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtef4zyia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtef4zyia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wifi" {...props}></Icon>
