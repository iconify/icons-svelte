<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlemv9bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlemv9bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:tab-plus" {...props}></Icon>
