<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxg9gvbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg9gvbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stack-exchange" {...props}></Icon>
