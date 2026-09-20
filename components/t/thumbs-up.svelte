<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0_z0tvmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0_z0tvmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:thumbs-up" {...props}></Icon>
