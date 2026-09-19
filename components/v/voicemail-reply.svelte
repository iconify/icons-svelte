<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blq0-bb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="blq0-bb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:voicemail-reply" {...props}></Icon>
