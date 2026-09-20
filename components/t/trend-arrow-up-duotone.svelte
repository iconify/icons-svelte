<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3yggvbbt.css';
import '../../css/z/zgmduh90n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3yggvbbt"/><path class="zgmduh90n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trend-arrow-up-duotone" {...props}></Icon>
