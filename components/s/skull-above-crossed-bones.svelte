<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glz_utbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="glz_utbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skull-above-crossed-bones" {...props}></Icon>
