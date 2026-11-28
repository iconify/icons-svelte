<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn4cq5nxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn4cq5nxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:washing-machine-alert" {...props}></Icon>
