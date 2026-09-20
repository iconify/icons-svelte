<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk2j-_b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bk2j-_b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spotify-original" {...props}></Icon>
