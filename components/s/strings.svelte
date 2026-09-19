<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzlw4kb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":476,"height":512};
const content = `<path class="nzlw4kb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:strings" {...props}></Icon>
