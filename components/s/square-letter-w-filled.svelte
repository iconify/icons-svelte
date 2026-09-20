<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvcbyubpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvcbyubpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-w-filled" {...props}></Icon>
