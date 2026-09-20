<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0-qt60mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0-qt60mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spotify" {...props}></Icon>
