<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmsnddboj.css';
import '../../css/j/jc8vjxbbg.css';
import '../../css/g/g68oh1czg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bmsnddboj"/><path class="jc8vjxbbg"/><path class="g68oh1czg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tea-cup-48" {...props}></Icon>
