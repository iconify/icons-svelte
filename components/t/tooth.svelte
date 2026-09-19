<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap5l40bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ap5l40bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tooth" {...props}></Icon>
