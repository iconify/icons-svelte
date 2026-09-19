<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am7xplpbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="am7xplpbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:team-outline" {...props}></Icon>
