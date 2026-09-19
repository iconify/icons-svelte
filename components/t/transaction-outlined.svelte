<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca-e6y59q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ca-e6y59q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:transaction-outlined" {...props}></Icon>
