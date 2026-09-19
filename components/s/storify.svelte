<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq17xxbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wq17xxbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:storify" {...props}></Icon>
