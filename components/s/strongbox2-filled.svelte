<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic988hg8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic988hg8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:strongbox2-filled" {...props}></Icon>
