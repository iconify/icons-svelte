<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meya6tb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meya6tb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sphere-shape-solid" {...props}></Icon>
