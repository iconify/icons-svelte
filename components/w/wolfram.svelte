<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwmahhbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmahhbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wolfram" {...props}></Icon>
