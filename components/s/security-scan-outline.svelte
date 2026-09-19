<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npg94ubpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="npg94ubpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:security-scan-outline" {...props}></Icon>
