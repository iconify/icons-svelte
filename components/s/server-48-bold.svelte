<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekgc8_cdh.css';
import '../../css/k/k9y255awr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ekgc8_cdh"/><path class="k9y255awr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-48-bold" {...props}></Icon>
