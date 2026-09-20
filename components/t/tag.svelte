<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzb5yt4nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vzb5yt4nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tag" {...props}></Icon>
