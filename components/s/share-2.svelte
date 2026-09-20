<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keyh69pew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="keyh69pew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:share-2" {...props}></Icon>
