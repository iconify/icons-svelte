<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as3krabjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="as3krabjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ruler-horizontal" {...props}></Icon>
