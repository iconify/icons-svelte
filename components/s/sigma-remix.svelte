<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqmv-acbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gqmv-acbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sigma-remix" {...props}></Icon>
