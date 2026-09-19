<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvssf56jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rvssf56jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-lightning-bolt-fill-12" {...props}></Icon>
