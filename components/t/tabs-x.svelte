<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqbde7trk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqbde7trk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tabs-x" {...props}></Icon>
