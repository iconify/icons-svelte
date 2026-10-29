<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccdihcchd.css';
import '../../css/n/nxxqhr_ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccdihcchd"/><path class="nxxqhr_ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:star" {...props}></Icon>
