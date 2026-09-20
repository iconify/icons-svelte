<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obzk38bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obzk38bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vitess" {...props}></Icon>
