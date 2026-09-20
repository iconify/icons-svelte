<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tirg10poz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tirg10poz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uber-dark" {...props}></Icon>
