<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo45pacgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo45pacgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:thumbs-up" {...props}></Icon>
