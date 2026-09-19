<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvr2oubro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="xvr2oubro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:sass" {...props}></Icon>
