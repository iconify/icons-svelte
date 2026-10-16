<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmx6sugjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mmx6sugjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:three-phase-48" {...props}></Icon>
