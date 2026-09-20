<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt6ic24ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt6ic24ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:soup-filled" {...props}></Icon>
