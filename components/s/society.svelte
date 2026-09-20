<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guc56fbsq.css';
import '../../css/b/bqc81ux0g.css';
import '../../css/a/amspxabxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guc56fbsq"/><path class="bqc81ux0g"/><path class="amspxabxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:society" {...props}></Icon>
