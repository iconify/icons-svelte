<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ho_hbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ho_hbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:schedule" {...props}></Icon>
