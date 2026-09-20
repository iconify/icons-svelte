<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_1qh8v2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_1qh8v2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-i-filled" {...props}></Icon>
