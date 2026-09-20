<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3jrlcbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d3jrlcbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sign-language-solid" {...props}></Icon>
