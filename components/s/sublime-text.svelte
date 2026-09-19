<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr3fq8j0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="kr3fq8j0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:sublime-text" {...props}></Icon>
