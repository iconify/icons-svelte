<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjnf610ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="pjnf610ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snows" {...props}></Icon>
