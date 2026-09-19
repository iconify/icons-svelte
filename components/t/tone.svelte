<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbh_168om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbh_168om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tone" {...props}></Icon>
