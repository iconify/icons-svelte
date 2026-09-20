<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqzfx8bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqzfx8bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trade-republic" {...props}></Icon>
