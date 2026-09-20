<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7zo2_bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v7zo2_bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:up-circle-outline" {...props}></Icon>
