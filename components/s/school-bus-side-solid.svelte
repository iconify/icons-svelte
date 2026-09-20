<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spdlrf7lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="spdlrf7lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:school-bus-side-solid" {...props}></Icon>
