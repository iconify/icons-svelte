<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmgvfub1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmgvfub1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tubi" {...props}></Icon>
