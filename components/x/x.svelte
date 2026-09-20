<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iymwg1b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iymwg1b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:x" {...props}></Icon>
