<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuyb_7bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yuyb_7bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:sauropod" {...props}></Icon>
