<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_xg8bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k3_xg8bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tool-fill" {...props}></Icon>
