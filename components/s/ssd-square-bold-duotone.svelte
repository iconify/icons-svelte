<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1u1sjbgx.css';
import '../../css/s/sqkdmebni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1u1sjbgx"/><path clip-rule="evenodd" class="sqkdmebni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ssd-square-bold-duotone" {...props}></Icon>
