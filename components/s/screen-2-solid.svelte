<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjh81_iow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gjh81_iow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screen-2-solid" {...props}></Icon>
