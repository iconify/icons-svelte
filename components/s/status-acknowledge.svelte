<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4n9_hbzl.css';
import '../../css/v/v1j9wac_l.css';
import '../../css/v/vbzy9bb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4n9_hbzl"/><path class="v1j9wac_l"/><path class="vbzy9bb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:status-acknowledge" {...props}></Icon>
