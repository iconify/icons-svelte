<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv6_e7b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cv6_e7b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:ruler-horizontal" {...props}></Icon>
