<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_h8gh8uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_h8gh8uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-square" {...props}></Icon>
