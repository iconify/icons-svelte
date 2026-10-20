<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-x_d5e7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-x_d5e7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ruler-dimension-line" {...props}></Icon>
