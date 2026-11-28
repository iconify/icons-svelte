<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chkt45bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chkt45bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shield-half" {...props}></Icon>
