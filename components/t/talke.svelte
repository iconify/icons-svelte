<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo5f_u6rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bo5f_u6rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:talke" {...props}></Icon>
