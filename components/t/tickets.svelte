<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-cae8ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zw-cae8ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tickets" {...props}></Icon>
