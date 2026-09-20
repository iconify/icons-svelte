<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msa3vwofs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msa3vwofs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:toggl-track" {...props}></Icon>
