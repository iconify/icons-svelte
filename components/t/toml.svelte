<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oce441wpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oce441wpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:toml" {...props}></Icon>
