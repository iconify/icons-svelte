<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us21q3b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us21q3b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rsocket" {...props}></Icon>
