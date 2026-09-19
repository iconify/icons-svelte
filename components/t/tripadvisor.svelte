<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qux8kuy1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1408};
const content = `<path class="qux8kuy1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tripadvisor" {...props}></Icon>
