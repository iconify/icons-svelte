<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5r6idh3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5r6idh3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:tablet" {...props}></Icon>
