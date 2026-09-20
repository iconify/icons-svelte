<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2i44lbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x2i44lbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:widget" {...props}></Icon>
