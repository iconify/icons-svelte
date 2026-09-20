<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq36f3btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rq36f3btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:table-col-after" {...props}></Icon>
