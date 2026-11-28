<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spthxyxzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spthxyxzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:truck" {...props}></Icon>
