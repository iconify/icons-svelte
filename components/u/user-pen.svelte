<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqyn1_03m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqyn1_03m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-pen" {...props}></Icon>
