<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otd35ob1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2200,"height":2200};
const content = `<path class="otd35ob1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:swr-light" {...props}></Icon>
