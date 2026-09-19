<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf6kgxbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf6kgxbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:volume" {...props}></Icon>
