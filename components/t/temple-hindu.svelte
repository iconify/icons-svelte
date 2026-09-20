<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/levnz9b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="levnz9b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:temple-hindu" {...props}></Icon>
