<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf73bwb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf73bwb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:y-combinator" {...props}></Icon>
