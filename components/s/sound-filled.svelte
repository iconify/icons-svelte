<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2scafb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x2scafb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sound-filled" {...props}></Icon>
