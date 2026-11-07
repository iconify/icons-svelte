<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/i/ii9soq6dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path clip-rule="evenodd" class="ii9soq6dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-bold-duotone" {...props}></Icon>
