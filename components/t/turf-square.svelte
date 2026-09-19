<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7gnshbpu.css';
import '../../css/k/ka8c7ss6d.css';
import '../../css/d/dh3rien5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="s7gnshbpu"/><path class="ka8c7ss6d"/><path class="dh3rien5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-square" {...props}></Icon>
