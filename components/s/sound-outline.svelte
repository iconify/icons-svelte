<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4-sp6bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b4-sp6bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sound-outline" {...props}></Icon>
