<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzzxcnbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pzzxcnbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:thumbtack-diagonal" {...props}></Icon>
