<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un-0dcbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un-0dcbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:star-half-round" {...props}></Icon>
