<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktja0ebaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktja0ebaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevrons-down-sharp-fill" {...props}></Icon>
