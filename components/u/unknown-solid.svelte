<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsq-xpqur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rsq-xpqur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:unknown-solid" {...props}></Icon>
