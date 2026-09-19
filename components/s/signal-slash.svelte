<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g97w46bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g97w46bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:signal-slash" {...props}></Icon>
