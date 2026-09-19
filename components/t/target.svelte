<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkaji56vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xkaji56vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:target" {...props}></Icon>
