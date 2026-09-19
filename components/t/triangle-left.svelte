<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mthpz1b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mthpz1b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-left" {...props}></Icon>
