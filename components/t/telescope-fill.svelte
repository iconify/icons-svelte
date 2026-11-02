<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io4e73bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io4e73bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:telescope-fill" {...props}></Icon>
