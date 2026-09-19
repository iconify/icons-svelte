<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knmzccbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="knmzccbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:twitter" {...props}></Icon>
