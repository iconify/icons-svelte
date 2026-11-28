<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7_o1pbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_o1pbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sailboat-solid" {...props}></Icon>
