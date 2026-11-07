<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/d/d-g40esoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="d-g40esoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-circle-bold-duotone" {...props}></Icon>
