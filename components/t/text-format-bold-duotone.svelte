<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulrix6h0r.css';
import '../../css/o/opnueljba.css';
import '../../css/t/t7w90pktp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulrix6h0r"/><path class="opnueljba"/><path class="t7w90pktp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-format-bold-duotone" {...props}></Icon>
