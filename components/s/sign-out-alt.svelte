<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht2tk_has.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ht2tk_has"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sign-out-alt" {...props}></Icon>
