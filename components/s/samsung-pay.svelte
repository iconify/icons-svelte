<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fym2klg0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fym2klg0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:samsung-pay" {...props}></Icon>
