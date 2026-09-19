<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzfwrfbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="rzfwrfbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spider" {...props}></Icon>
