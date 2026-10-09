<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvh346bsa.css';
import '../../css/k/kqy72r22k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uvh346bsa"/><path class="kqy72r22k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:undo-48" {...props}></Icon>
