<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drjbh1b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="drjbh1b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:telegram-original" {...props}></Icon>
