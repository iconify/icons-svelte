<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeow0krbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zeow0krbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:wallet2" {...props}></Icon>
