<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a90emgbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a90emgbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wry-smile-filled" {...props}></Icon>
