<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhjhcebay.css';
import '../../css/s/sq8m2mg-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhjhcebay"/><path class="sq8m2mg-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tickets" {...props}></Icon>
