<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ratr-0b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":974,"height":1024};
const content = `<path class="ratr-0b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:whmcs" {...props}></Icon>
