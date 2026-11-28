<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw_dihbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw_dihbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sun-plus" {...props}></Icon>
