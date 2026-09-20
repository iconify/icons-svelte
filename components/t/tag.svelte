<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwy_4lplo.css';
import '../../css/n/n2zz0dpiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dwy_4lplo"/><ellipse class="n2zz0dpiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:tag" {...props}></Icon>
