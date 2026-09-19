<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugo44b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gugo44b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:scan-small" {...props}></Icon>
