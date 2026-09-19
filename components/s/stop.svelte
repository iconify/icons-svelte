<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxswfgjtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rxswfgjtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stop" {...props}></Icon>
