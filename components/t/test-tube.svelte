<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izqfe9b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="izqfe9b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:test-tube" {...props}></Icon>
