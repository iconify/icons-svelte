<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyhrc7b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gyhrc7b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:speedalt" {...props}></Icon>
