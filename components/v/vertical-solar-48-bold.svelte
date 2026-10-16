<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esbwj800h.css';
import '../../css/x/xad-8sbqh.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="esbwj800h"/><path class="xad-8sbqh"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vertical-solar-48-bold" {...props}></Icon>
