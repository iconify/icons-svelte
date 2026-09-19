<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6m002bvn.css';
import '../../css/s/sgxi3fe_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="f6m002bvn"/><path class="sgxi3fe_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:search-fill-12" {...props}></Icon>
