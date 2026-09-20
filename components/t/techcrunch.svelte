<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m49-_o60c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m49-_o60c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:techcrunch" {...props}></Icon>
