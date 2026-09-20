<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgy3_4bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgy3_4bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yew" {...props}></Icon>
