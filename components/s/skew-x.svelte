<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/humv9earr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="humv9earr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:skew-x" {...props}></Icon>
