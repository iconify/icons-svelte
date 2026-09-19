<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2oh615lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c2oh615lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sun-outlined" {...props}></Icon>
