<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6a5dms5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f6a5dms5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:section" {...props}></Icon>
