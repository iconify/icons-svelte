<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6wjdqwxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6wjdqwxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-2-line" {...props}></Icon>
