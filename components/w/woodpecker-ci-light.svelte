<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxl7tlbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxl7tlbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:woodpecker-ci-light" {...props}></Icon>
