<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/let3-10tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="let3-10tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teslamate-light" {...props}></Icon>
