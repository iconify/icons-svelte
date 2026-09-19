<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2gna1b5o.css';
import '../../css/s/sgyebwbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="t2gna1b5o"/><path class="sgyebwbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:x-circle" {...props}></Icon>
