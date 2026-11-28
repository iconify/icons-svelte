<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs90746zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs90746zt primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:type-vertical-duotone" {...props}></Icon>
