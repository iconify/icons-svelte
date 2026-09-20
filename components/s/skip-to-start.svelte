<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z16tn7gsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="z16tn7gsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:skip-to-start" {...props}></Icon>
