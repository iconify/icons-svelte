<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr_hp9bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jr_hp9bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:xamarin" {...props}></Icon>
