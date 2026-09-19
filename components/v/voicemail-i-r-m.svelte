<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1av9qnsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a1av9qnsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:voicemail-i-r-m" {...props}></Icon>
