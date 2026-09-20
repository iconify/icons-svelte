<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-00eccfu.css';
import '../../css/i/i6o-cqbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-00eccfu"/><path class="i6o-cqbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tracked-by-closed-not-planned-16" {...props}></Icon>
