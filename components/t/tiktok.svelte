<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps0o97bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ps0o97bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:tiktok" {...props}></Icon>
