<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry5_eaccq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry5_eaccq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:saw-solid" {...props}></Icon>
