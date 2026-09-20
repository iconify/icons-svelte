<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdfqr6ksx.css';
import '../../css/t/tqdn9_b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdfqr6ksx"/><path class="tqdn9_b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:splitpro-dark" {...props}></Icon>
