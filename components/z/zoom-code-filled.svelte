<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv-60l-dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv-60l-dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-code-filled" {...props}></Icon>
