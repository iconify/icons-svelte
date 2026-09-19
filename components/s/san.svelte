<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug3hazb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":425,"height":512};
const content = `<path class="ug3hazb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:san" {...props}></Icon>
