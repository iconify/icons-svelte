<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4a8etro.css';
import '../../css/n/nwj7terdc.css';
import '../../css/l/lh639nb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4a8etro"/><path class="nwj7terdc"/><path class="lh639nb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-numeric-down" {...props}></Icon>
