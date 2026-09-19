<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7dcahbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="d7dcahbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:stethoscope" {...props}></Icon>
