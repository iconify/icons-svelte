<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf43ddl1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pf43ddl1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-twitter" {...props}></Icon>
