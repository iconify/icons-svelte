<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f80wugblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f80wugblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:truck-outlined" {...props}></Icon>
