<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k983gnjgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k983gnjgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-pinterest" {...props}></Icon>
