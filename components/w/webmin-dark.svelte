<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anam2owfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anam2owfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webmin-dark" {...props}></Icon>
