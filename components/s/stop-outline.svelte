<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brt7te-9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="brt7te-9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:stop-outline" {...props}></Icon>
