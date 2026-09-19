<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2_lm1byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x2_lm1byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-patient" {...props}></Icon>
