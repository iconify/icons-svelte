<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3lxracrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e3lxracrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-secret" {...props}></Icon>
