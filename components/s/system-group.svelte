<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paurdn42f.css';
import '../../css/w/ws0xuezat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paurdn42f"/><path class="ws0xuezat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:system-group" {...props}></Icon>
