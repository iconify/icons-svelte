<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqacljb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqacljb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-dots" {...props}></Icon>
