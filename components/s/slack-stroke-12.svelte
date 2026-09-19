<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkj7g0bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xkj7g0bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:slack-stroke-12" {...props}></Icon>
