<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb7_vib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb7_vib4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:single-quotes-r" {...props}></Icon>
