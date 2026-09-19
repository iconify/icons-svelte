<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7hiwxbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="l7hiwxbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tag-circle" {...props}></Icon>
