<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g74y0wb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g74y0wb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rotated-forbid" {...props}></Icon>
