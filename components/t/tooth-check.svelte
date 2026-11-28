<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh8dgebiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8dgebiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tooth-check" {...props}></Icon>
