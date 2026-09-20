<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv3iph2kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv3iph2kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:visual-paradigm" {...props}></Icon>
