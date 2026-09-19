<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzatnb48s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bzatnb48s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:wifi-2" {...props}></Icon>
