<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qued2fh4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qued2fh4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-linear" {...props}></Icon>
