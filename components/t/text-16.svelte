<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi9xwzxrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yi9xwzxrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:text-16" {...props}></Icon>
