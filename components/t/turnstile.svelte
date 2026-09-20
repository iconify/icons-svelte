<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzmpkfi4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uzmpkfi4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:turnstile" {...props}></Icon>
