<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irngtbb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irngtbb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:threads" {...props}></Icon>
