<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8gtq9blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8gtq9blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typebot-dark" {...props}></Icon>
