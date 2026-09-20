<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib0cctbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib0cctbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:thumbs-down" {...props}></Icon>
