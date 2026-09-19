<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp_jgrb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kp_jgrb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sort-ascending-outline" {...props}></Icon>
