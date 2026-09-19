<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb0msfbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tb0msfbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-web-awesome" {...props}></Icon>
