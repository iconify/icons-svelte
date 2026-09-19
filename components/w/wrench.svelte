<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oripv7bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oripv7bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:wrench" {...props}></Icon>
