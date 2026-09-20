<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9xm-gbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n9xm-gbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:viber" {...props}></Icon>
