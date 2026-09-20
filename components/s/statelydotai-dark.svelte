<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek6sb0brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":405};
const content = `<path class="ek6sb0brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:statelydotai-dark" {...props}></Icon>
