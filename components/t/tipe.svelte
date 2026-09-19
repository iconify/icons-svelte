<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndc5i5bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":331,"height":512};
const content = `<path class="ndc5i5bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tipe" {...props}></Icon>
