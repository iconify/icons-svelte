<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mll4yq1pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mll4yq1pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:umbrella-line" {...props}></Icon>
