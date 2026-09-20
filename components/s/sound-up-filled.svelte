<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agai12bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agai12bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sound-up-filled" {...props}></Icon>
