<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syv80hb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="syv80hb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:send-alt" {...props}></Icon>
