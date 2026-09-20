<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-cqv87wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-cqv87wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:victoriametrics" {...props}></Icon>
