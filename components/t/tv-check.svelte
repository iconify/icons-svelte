<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxbd9gbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxbd9gbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tv-check" {...props}></Icon>
