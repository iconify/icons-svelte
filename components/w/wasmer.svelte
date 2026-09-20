<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l70wbacno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l70wbacno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wasmer" {...props}></Icon>
