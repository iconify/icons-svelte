<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6el7ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vn6el7ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:synagogue" {...props}></Icon>
