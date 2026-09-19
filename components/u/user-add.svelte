<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khay4rsjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="khay4rsjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:user-add" {...props}></Icon>
