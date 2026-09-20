<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0b90rb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v0b90rb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:west" {...props}></Icon>
