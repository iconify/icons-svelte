<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvpsdxbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cvpsdxbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:tennis-ball" {...props}></Icon>
