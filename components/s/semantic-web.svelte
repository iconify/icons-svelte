<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-mluac3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-mluac3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:semantic-web" {...props}></Icon>
