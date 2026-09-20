<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pykl44r4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pykl44r4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:square-shape" {...props}></Icon>
