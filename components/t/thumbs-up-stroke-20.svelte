<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv1dmxb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qv1dmxb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:thumbs-up-stroke-20" {...props}></Icon>
