<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjtcw51ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kjtcw51ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:smile-outline" {...props}></Icon>
