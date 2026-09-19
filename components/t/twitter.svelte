<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffd_xfbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ffd_xfbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:twitter" {...props}></Icon>
