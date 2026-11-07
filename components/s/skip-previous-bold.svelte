<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kerg8qktr.css';
import '../../css/w/wjmxqyb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kerg8qktr"/><path class="wjmxqyb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skip-previous-bold" {...props}></Icon>
