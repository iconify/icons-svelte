<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i47kys6fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i47kys6fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xls-fill" {...props}></Icon>
