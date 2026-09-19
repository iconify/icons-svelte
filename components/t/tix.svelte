<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1yq4quw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dt1yq4quw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tix" {...props}></Icon>
