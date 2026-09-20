<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8chphb8w.css';
import '../../css/k/kpuc3bbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8chphb8w"/><path clip-rule="evenodd" class="kpuc3bbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:select-all-16" {...props}></Icon>
