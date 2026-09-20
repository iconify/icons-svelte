<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szpbw-bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szpbw-bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:step-backward" {...props}></Icon>
