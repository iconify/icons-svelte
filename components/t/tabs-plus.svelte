<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_c1d8fvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_c1d8fvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tabs-plus" {...props}></Icon>
