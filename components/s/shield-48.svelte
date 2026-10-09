<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lld64mb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lld64mb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-48" {...props}></Icon>
