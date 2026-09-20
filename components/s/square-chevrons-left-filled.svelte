<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_3ee6a8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_3ee6a8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-chevrons-left-filled" {...props}></Icon>
