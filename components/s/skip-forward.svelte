<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wci2ylbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wci2ylbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:skip-forward" {...props}></Icon>
