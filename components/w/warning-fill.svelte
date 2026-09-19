<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prjy8z40i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="prjy8z40i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:warning-fill" {...props}></Icon>
