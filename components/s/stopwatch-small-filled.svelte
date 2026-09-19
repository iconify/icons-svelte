<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9snvqbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r9snvqbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:stopwatch-small-filled" {...props}></Icon>
