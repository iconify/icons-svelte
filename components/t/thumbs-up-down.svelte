<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feo0r_n-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feo0r_n-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thumbs-up-down" {...props}></Icon>
