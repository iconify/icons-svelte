<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjy_robzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjy_robzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rubocop" {...props}></Icon>
