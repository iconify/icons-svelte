<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg8gem3ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg8gem3ww primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-heart-duotone" {...props}></Icon>
