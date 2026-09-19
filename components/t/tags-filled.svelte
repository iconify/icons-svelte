<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv4waujmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fv4waujmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tags-filled" {...props}></Icon>
