<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj--0qmpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj--0qmpo primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spiral-duotone" {...props}></Icon>
