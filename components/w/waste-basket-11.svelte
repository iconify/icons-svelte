<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jos6di89e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jos6di89e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:waste-basket-11" {...props}></Icon>
