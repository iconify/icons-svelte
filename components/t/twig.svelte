<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn6a84b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":409,"height":512};
const content = `<path class="sn6a84b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:twig" {...props}></Icon>
