<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k550qgo1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k550qgo1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-plus-solid" {...props}></Icon>
