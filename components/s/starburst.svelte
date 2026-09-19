<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm1f1rrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="adm1f1rrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:starburst" {...props}></Icon>
