<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg8tafxco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg8tafxco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:thermometer" {...props}></Icon>
