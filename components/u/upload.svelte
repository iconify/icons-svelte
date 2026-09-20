<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2ygjsqjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="m2ygjsqjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:upload" {...props}></Icon>
