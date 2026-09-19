<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5itgc9oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s5itgc9oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:user-switch-outlined" {...props}></Icon>
