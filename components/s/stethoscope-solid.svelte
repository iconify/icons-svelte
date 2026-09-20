<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be_gcblti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="be_gcblti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stethoscope-solid" {...props}></Icon>
