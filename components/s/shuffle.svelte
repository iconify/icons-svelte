<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-vi64b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n-vi64b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:shuffle" {...props}></Icon>
