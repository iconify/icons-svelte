<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esk15tbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="esk15tbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rss-solid" {...props}></Icon>
