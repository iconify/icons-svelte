<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--2xbb1l.css';
import '../../css/u/u-db7hb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v--2xbb1l"/><path class="u-db7hb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:youtube" {...props}></Icon>
