<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx9l4gb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wx9l4gb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:separator" {...props}></Icon>
