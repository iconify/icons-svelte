<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n82zcy6-h.css';
import '../../css/c/cwu8tob-z.css';
import '../../css/n/nwzo9bcnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n82zcy6-h"/><path class="cwu8tob-z"/><path class="nwzo9bcnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:search-plus" {...props}></Icon>
