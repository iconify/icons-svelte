<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o533a9f5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="o533a9f5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:zoom-in" {...props}></Icon>
