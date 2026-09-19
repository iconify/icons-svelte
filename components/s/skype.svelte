<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu04n28xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vu04n28xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:skype" {...props}></Icon>
