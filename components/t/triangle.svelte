<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl-7bcp8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-7bcp8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:triangle" {...props}></Icon>
