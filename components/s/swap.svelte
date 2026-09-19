<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuf17ubvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuf17ubvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:swap" {...props}></Icon>
