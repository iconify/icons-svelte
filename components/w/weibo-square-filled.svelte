<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub-6oev6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ub-6oev6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:weibo-square-filled" {...props}></Icon>
