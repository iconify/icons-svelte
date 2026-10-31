<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu9nf7cwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9nf7cwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:switch-camera-gloss" {...props}></Icon>
