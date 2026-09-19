<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcfak91qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcfak91qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thumbs-down" {...props}></Icon>
