<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsy565b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsy565b3b primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:type-size-duotone" {...props}></Icon>
