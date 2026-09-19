<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9wxmqbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9wxmqbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-left-light" {...props}></Icon>
