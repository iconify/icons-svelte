<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek0xau4pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek0xau4pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:windowsxp" {...props}></Icon>
