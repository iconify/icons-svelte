<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_s8-1u6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_s8-1u6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:shape-rhombus" {...props}></Icon>
