<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ft8ykqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y7ft8ykqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:telegram" {...props}></Icon>
