<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4cexpbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4cexpbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-03" {...props}></Icon>
