<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9nes1u6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9nes1u6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:vertical-ellipsis" {...props}></Icon>
