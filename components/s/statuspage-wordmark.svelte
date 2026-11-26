<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7esww5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nl7esww5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:statuspage-wordmark" {...props}></Icon>
