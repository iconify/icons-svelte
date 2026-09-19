<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw5iv4tez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cw5iv4tez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:server-fault" {...props}></Icon>
