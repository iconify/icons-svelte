<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfml8eqyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfml8eqyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wattbox-dark" {...props}></Icon>
