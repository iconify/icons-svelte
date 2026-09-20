<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mll5hmbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="mll5hmbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:squre-shape" {...props}></Icon>
