<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pccwcw4ye.css';
import '../../css/a/alckcbcdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pccwcw4ye"/><path class="alckcbcdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:up-left" {...props}></Icon>
