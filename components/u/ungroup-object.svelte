<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afv9dwb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="afv9dwb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ungroup-object" {...props}></Icon>
