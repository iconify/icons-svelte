<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-n64rb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="o-n64rb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:xing" {...props}></Icon>
