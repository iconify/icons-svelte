<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukh7uprul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ukh7uprul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:wan" {...props}></Icon>
