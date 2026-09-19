<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqj5utbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kqj5utbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:symphony" {...props}></Icon>
