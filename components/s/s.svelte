<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-kxx5bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-kxx5bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:s" {...props}></Icon>
