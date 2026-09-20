<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz6i_lbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz6i_lbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:similarweb" {...props}></Icon>
