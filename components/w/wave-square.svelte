<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcr26mbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcr26mbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wave-square" {...props}></Icon>
