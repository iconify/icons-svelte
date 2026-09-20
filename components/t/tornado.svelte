<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2mq70njp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t2mq70njp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tornado" {...props}></Icon>
