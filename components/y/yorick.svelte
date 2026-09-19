<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j286beboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":417,"height":512};
const content = `<path class="j286beboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yorick" {...props}></Icon>
