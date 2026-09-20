<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phywesbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phywesbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wwise" {...props}></Icon>
