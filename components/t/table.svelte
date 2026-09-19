<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ajcf0wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8ajcf0wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:table" {...props}></Icon>
