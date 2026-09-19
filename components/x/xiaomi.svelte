<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5nwiwp8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l5nwiwp8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:xiaomi" {...props}></Icon>
