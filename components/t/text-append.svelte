<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko-5hi22e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ko-5hi22e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-append" {...props}></Icon>
