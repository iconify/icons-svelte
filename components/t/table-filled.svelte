<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws4zpwkgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4zpwkgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-filled" {...props}></Icon>
