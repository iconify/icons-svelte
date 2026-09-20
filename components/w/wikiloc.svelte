<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4u8idh_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4u8idh_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wikiloc" {...props}></Icon>
