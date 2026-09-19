<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx777smff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nx777smff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:scale-unbalanced-flip" {...props}></Icon>
