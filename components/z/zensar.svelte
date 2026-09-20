<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s35--qp5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s35--qp5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zensar" {...props}></Icon>
