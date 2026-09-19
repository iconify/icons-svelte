<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdypsia2b.css';
import '../../css/h/hztfv9bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdypsia2b"/><path class="hztfv9bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:templates-outlined" {...props}></Icon>
