<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjd-5qbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjd-5qbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stirling-pdf" {...props}></Icon>
