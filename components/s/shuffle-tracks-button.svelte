<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaepzkbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="gaepzkbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:shuffle-tracks-button" {...props}></Icon>
