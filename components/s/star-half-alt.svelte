<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpbdes8bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpbdes8bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:star-half-alt" {...props}></Icon>
