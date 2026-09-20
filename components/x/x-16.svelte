<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu7-jgb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pu7-jgb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:x-16" {...props}></Icon>
