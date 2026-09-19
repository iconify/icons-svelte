<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3m5hu29g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e3m5hu29g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni7121-box-filled" {...props}></Icon>
