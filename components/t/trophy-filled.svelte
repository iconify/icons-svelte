<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7u1zqfvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c7u1zqfvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:trophy-filled" {...props}></Icon>
