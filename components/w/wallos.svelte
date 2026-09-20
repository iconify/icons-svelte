<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cixcpjbxu.css';
import '../../css/m/mr5bnpbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cixcpjbxu"/><path class="mr5bnpbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wallos" {...props}></Icon>
