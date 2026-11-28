<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxnw1wbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxnw1wbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sticky-note-x" {...props}></Icon>
