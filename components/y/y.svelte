<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-82kqbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x-82kqbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:y" {...props}></Icon>
