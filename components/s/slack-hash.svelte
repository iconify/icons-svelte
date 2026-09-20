<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-0k38b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x-0k38b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:slack-hash" {...props}></Icon>
