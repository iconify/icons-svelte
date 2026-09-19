<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc-mqm-1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nc-mqm-1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wallaby" {...props}></Icon>
