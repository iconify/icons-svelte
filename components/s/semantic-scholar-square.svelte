<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sihm51ipd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sihm51ipd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:semantic-scholar-square" {...props}></Icon>
