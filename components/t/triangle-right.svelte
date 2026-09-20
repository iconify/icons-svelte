<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cozkiep2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cozkiep2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:triangle-right" {...props}></Icon>
