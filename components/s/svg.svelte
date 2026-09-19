<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2o_74so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jr2o_74so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:svg" {...props}></Icon>
