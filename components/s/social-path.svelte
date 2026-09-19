<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwzctubkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nwzctubkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-path" {...props}></Icon>
