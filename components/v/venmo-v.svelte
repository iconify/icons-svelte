<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3829eb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m3829eb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:venmo-v" {...props}></Icon>
