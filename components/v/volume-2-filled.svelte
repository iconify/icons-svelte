<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3j0fwjec.css';
import '../../css/o/ou4giibdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3j0fwjec"/><path class="ou4giibdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:volume-2-filled" {...props}></Icon>
