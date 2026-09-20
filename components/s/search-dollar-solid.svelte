<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak5-9jb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ak5-9jb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:search-dollar-solid" {...props}></Icon>
