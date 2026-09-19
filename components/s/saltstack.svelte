<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8cl6ubas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":512};
const content = `<path class="h8cl6ubas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:saltstack" {...props}></Icon>
