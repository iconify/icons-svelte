<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8jkilbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8jkilbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-shade" {...props}></Icon>
