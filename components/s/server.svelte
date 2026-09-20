<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjdee8b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sjdee8b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:server" {...props}></Icon>
