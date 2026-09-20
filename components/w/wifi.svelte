<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy6di_b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6di_b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi" {...props}></Icon>
