<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn8lobeas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hn8lobeas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:solution" {...props}></Icon>
