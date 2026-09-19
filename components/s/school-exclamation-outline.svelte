<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r92u9ifpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r92u9ifpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-exclamation-outline" {...props}></Icon>
