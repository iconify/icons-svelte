<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgi-stgjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgi-stgjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:takeoff-fill" {...props}></Icon>
