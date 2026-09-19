<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8l6k8asg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d8l6k8asg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:strikethrough" {...props}></Icon>
