<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1y8fp8ua.css';
import '../../css/l/lm9p31gmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1y8fp8ua"/><path class="lm9p31gmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:terminal-outlined" {...props}></Icon>
