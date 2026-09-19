<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7h66w8ve.css';
import '../../css/c/cwbr59xig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o7h66w8ve"/><path class="cwbr59xig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subnet-acl-rules" {...props}></Icon>
