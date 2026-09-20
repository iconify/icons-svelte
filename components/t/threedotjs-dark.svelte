<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz96dybco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz96dybco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:threedotjs-dark" {...props}></Icon>
