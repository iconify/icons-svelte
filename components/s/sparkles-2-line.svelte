<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m73rx1-kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m73rx1-kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sparkles-2-line" {...props}></Icon>
