<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qftym_bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qftym_bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voilib-dark" {...props}></Icon>
