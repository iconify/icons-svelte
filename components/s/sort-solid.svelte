<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkpe6tbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkpe6tbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sort-solid" {...props}></Icon>
