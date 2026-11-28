<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjql5_bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjql5_bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:save" {...props}></Icon>
