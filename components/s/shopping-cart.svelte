<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa8f_iukb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-4};
const content = `<path class="wa8f_iukb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shopping-cart" {...props}></Icon>
