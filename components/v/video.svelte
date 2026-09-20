<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxdz69ddd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rxdz69ddd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:video" {...props}></Icon>
