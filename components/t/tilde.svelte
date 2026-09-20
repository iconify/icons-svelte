<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf4ba4bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf4ba4bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tilde" {...props}></Icon>
