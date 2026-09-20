<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjun9vdeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="wjun9vdeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:volume-down" {...props}></Icon>
