<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o75u76x7m.css';
import '../../css/u/u0uqtx1rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o75u76x7m"/><path class="u0uqtx1rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:siderbar-bold-duotone" {...props}></Icon>
