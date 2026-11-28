<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzzd7pb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzzd7pb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sun-rain-solid" {...props}></Icon>
