<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw2qafb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw2qafb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-back-fill-round" {...props}></Icon>
