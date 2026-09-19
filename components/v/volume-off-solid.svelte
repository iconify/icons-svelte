<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6_n1cb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6_n1cb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:volume-off-solid" {...props}></Icon>
