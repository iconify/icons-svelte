<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxi-gcmxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="jxi-gcmxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:scorp" {...props}></Icon>
