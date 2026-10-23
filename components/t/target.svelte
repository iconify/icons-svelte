<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st_zqywsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st_zqywsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:target" {...props}></Icon>
