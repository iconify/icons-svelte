<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lerqotbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lerqotbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spy-circle" {...props}></Icon>
