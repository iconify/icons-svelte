<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbl1pdi-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbl1pdi-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:time-back" {...props}></Icon>
