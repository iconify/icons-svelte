<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ii5ybol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o1ii5ybol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:yahoo" {...props}></Icon>
