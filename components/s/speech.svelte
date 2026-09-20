<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1f6iwq3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b1f6iwq3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:speech" {...props}></Icon>
