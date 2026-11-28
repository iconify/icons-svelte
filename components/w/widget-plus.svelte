<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz4i_1bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz4i_1bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:widget-plus" {...props}></Icon>
