<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px_ujgm9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px_ujgm9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:user-outline" {...props}></Icon>
