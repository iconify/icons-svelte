<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv60hwb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv60hwb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ticket-percent" {...props}></Icon>
