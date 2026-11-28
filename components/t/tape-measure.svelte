<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i24cc3bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i24cc3bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tape-measure" {...props}></Icon>
