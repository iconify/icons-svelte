<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm1-l0cmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jm1-l0cmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:stop-circle-20-solid" {...props}></Icon>
