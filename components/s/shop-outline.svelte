<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sig6v4bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sig6v4bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:shop-outline" {...props}></Icon>
