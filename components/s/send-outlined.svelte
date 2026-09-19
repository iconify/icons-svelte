<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3bzb714c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n3bzb714c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:send-outlined" {...props}></Icon>
