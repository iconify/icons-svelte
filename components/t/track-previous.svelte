<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu--34z8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iu--34z8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:track-previous" {...props}></Icon>
