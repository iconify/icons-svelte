<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-rlecbga.css';
import '../../css/g/gj8v89bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r-rlecbga"/><path class="gj8v89bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-20-bold" {...props}></Icon>
