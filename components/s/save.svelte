<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yptd0dbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="yptd0dbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:save" {...props}></Icon>
