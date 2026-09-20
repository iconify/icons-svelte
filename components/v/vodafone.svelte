<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_8rf2bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_8rf2bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vodafone" {...props}></Icon>
