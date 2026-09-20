<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6jbv-bsq.css';
import '../../css/t/tvn_kseps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6jbv-bsq"/><path class="tvn_kseps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-woman-home-bold" {...props}></Icon>
