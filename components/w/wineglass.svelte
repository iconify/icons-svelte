<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul-fvud4v.css';
import '../../css/j/jvhn8ub7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ul-fvud4v"/><path class="jvhn8ub7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wineglass" {...props}></Icon>
