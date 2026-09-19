<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h20o-8bsr.css';
import '../../css/m/mb7553tox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h20o-8bsr"/><path class="mb7553tox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-foursquare" {...props}></Icon>
