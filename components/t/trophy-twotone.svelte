<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6eec_-wn.css';
import '../../css/f/f-uh8goxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y6eec_-wn"/><path class="f-uh8goxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:trophy-twotone" {...props}></Icon>
