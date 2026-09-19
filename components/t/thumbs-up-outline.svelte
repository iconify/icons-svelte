<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppwiyuuhj.css';
import '../../css/g/gdr7v9b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ppwiyuuhj"/><path class="gdr7v9b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thumbs-up-outline" {...props}></Icon>
