<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzyun4bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzyun4bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-check" {...props}></Icon>
