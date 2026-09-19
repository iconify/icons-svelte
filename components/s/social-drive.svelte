<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krcsaxb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="krcsaxb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-drive" {...props}></Icon>
