<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpwc0-b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gpwc0-b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tags-outlined" {...props}></Icon>
