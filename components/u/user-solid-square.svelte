<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwz24ebrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zwz24ebrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:user-solid-square" {...props}></Icon>
