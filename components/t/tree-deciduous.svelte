<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsds0r5em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsds0r5em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tree-deciduous" {...props}></Icon>
