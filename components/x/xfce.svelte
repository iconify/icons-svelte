<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3r8bvw8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3r8bvw8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xfce" {...props}></Icon>
