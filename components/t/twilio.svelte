<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5m2bmbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z5m2bmbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:twilio" {...props}></Icon>
