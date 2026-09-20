<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae2ur5upl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ae2ur5upl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wheelchair-solid" {...props}></Icon>
