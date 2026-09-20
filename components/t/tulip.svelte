<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuhrwsh0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fuhrwsh0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tulip" {...props}></Icon>
