<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw0ks3bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fw0ks3bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:snippets" {...props}></Icon>
