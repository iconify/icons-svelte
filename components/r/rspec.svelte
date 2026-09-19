<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz97jizsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lz97jizsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rspec" {...props}></Icon>
