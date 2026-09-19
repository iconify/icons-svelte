<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmx2awujk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmx2awujk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:terminal" {...props}></Icon>
