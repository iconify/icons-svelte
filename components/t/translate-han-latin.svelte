<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy2e0xhtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xy2e0xhtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-han-latin" {...props}></Icon>
