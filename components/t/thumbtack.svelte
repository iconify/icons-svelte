<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z97jznbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="z97jznbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:thumbtack" {...props}></Icon>
