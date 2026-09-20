<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go7za8b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="go7za8b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:yin-yang" {...props}></Icon>
