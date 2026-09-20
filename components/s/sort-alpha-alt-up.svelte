<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk40d6bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk40d6bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-alpha-alt-up" {...props}></Icon>
