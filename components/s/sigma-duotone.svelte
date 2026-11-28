<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbbrp6yqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbbrp6yqf primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sigma-duotone" {...props}></Icon>
