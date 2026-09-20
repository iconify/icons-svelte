<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hee5pyz_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hee5pyz_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sms" {...props}></Icon>
