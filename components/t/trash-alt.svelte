<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha6wzbc4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha6wzbc4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:trash-alt" {...props}></Icon>
