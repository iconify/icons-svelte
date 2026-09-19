<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuwlt3xsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tuwlt3xsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:slack-circle-fill" {...props}></Icon>
