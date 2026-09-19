<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1zcd-6-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="l1zcd-6-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-snapchat" {...props}></Icon>
