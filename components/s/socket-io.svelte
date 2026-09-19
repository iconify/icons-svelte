<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp0bzp2ut.css';
import '../../css/e/epusddcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b tp0bzp2ut"/><path class="b epusddcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:socket-io" {...props}></Icon>
