<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq8jowtcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq8jowtcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wegame" {...props}></Icon>
