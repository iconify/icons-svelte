<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzzpiv8ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dzzpiv8ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:triangular-ruler" {...props}></Icon>
