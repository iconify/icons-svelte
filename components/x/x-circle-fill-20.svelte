<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxuzxz-mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vxuzxz-mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-circle-fill-20" {...props}></Icon>
