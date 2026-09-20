<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc5aw5fhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qc5aw5fhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:the-red-yeti" {...props}></Icon>
