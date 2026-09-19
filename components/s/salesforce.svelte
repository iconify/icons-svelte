<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9yi8_btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r9yi8_btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:salesforce" {...props}></Icon>
