<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5n3t9bfx.css';
import '../../css/b/btyzzq5no.css';
import '../../css/c/cac_93bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s5n3t9bfx"/><path class="btyzzq5no"/><path class="cac_93bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tailings-dam-20-bold" {...props}></Icon>
