<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsge839ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsge839ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:volume-minus" {...props}></Icon>
