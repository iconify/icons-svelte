<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nom8aq2sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="nom8aq2sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:sailing" {...props}></Icon>
