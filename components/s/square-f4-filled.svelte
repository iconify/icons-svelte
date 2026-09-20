<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_ni9ugb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_ni9ugb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-f4-filled" {...props}></Icon>
