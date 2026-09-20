<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5z-95bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5z-95bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:swiggy" {...props}></Icon>
