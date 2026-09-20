<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm4s1d5tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fm4s1d5tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stripe" {...props}></Icon>
