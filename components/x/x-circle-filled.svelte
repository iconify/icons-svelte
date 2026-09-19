<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-89rbqjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-89rbqjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:x-circle-filled" {...props}></Icon>
