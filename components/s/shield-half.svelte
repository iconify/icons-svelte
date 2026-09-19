<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl5_wzbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl5_wzbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shield-half" {...props}></Icon>
