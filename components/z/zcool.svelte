<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q54_4lbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q54_4lbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zcool" {...props}></Icon>
