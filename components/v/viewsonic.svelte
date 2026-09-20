<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi6fgjbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200.575,"height":32.571};
const content = `<path class="hi6fgjbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:viewsonic" {...props}></Icon>
