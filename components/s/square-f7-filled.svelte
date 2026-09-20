<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isw9jyb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isw9jyb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-f7-filled" {...props}></Icon>
