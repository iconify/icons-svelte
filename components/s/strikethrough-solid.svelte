<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8d7i3boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l8d7i3boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:strikethrough-solid" {...props}></Icon>
