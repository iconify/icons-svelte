<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myha_s0_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myha_s0_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-2-fill" {...props}></Icon>
