<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4a4kabvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="c4a4kabvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squareviber" {...props}></Icon>
