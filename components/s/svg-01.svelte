<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvs_ubbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvs_ubbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:svg-01" {...props}></Icon>
