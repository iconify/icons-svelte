<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypr13qj_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ypr13qj_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:steem" {...props}></Icon>
