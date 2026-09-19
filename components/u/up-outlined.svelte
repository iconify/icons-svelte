<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/attc-db7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="attc-db7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:up-outlined" {...props}></Icon>
