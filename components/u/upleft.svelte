<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amf6q6f-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="amf6q6f-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:upleft" {...props}></Icon>
