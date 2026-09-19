<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/webk14bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="webk14bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:usdc" {...props}></Icon>
