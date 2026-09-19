<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoenl6jag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aoenl6jag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tkn" {...props}></Icon>
