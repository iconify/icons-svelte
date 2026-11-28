<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynlga7bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynlga7bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:theater-masks" {...props}></Icon>
