<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ownzj_vcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ownzj_vcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set-left-centre" {...props}></Icon>
