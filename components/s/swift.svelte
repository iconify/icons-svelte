<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef8-76t7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ef8-76t7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:swift" {...props}></Icon>
