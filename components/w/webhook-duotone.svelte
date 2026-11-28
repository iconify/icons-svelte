<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4tknlb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y4tknlb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:webhook-duotone" {...props}></Icon>
