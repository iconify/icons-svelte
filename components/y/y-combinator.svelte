<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfdxomh6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wfdxomh6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:y-combinator" {...props}></Icon>
