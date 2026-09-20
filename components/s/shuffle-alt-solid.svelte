<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrg2nnkup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrg2nnkup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shuffle-alt-solid" {...props}></Icon>
