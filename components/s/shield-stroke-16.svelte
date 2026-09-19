<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbc1vlpwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dbc1vlpwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shield-stroke-16" {...props}></Icon>
