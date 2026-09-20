<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs80a_qke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs80a_qke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-normal2" {...props}></Icon>
